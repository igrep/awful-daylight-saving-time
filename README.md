# Awful Daylight Saving Time

サマータイムの 恐ろしさ・よさ まとめ

## 背景・目的

2020年の東京オリンピック・パラリンピックの酷暑対策として、夏の時間を2時間繰り上げるサマータイム（夏時間）を、2019年・2020年の2年間限定で導入するという検討を、政府が始めたそうです。

[【東京五輪】酷暑対策でサマータイム導入へ　秋の臨時国会で議員立法　３１、３２年限定（1/2ページ） - 産経ニュース](https://www.sankei.com/politics/news/180806/plt1808060002-n1.html)

酷暑対策という名目であれば競技時間や鉄道の特別ダイヤを設定するなど、遙かに影響範囲の小さい変更で対応できるであろうにもかかわらず、わざわざ日本のあらゆるシステムで対応が必要な対策を講じるという時点で大きな疑問を感じます。  
同様に、サマータイムに対して否定的な意見は私の観測範囲内で、Twitterやはてなブックマークにおける各発言に見られます。

一方で、私はこれまでサマータイムに関わるバグや障害、その他の問題の当事者となった経験がなく、具体的に起こる問題についての見識が不足しています。  
そこで、今後私がサマータイムに賛成するにせよ反対するにせよ、サマータイムに関わる様々な情報、とりわけ過去に問題となった事例を集めることで、意見を述べる際の材料としたいと思います。  
そのためこのリポジトリーでは、サマータイムの悪い（あるいは良い）側面について、「ウェブサイトや書籍などの情報源」と「その関係する箇所の（日本語での）要約」を中心に収集します。

GitHubに公開していることから察せられるとおり、Pull requestやIssue報告による情報提供は強く歓迎します。

## サマータイムの悪い側面について


### システム修正に関わる問題（過去発生したバグ、障害など）

- 組み込み機器など、更新が困難なコンピューターが存在する。
    - [Windowsのサマータイム対応、組み込み機器に難題　　：日本経済新聞](https://www.nikkei.com/article/DGXMZO33991670Z00C18A8000000/)  
      > ただし、Windowsは決済端末やキオスク端末、工場設備などの組み込み機器にも多く使われている。これらの機器でWindows Updateを適用しにくい場合、サマータイム対応が難題になる可能性がある
- （サマータイムを長年実施している国の人が作ったソフトウェアであっても）カレンダーやアラームなどの動作がおかしくなる
    - [Yep, There's A Daylight Savings Time Bug In iOS 7.0.6 - Cult of Mac](https://www.cultofmac.com/269245/yep-theres-daylight-savings-time-bug-ios-7-0-6/)  
      > Apple has had bugs come up in iOS after the switch to Daylight Savings Time in 2010, 2011, and 2012, while 2013 saw a similar New Year’s Bug screw up Do Not Disturb for device owners. Now here we are in 2014. Does iOS 7 contain a Daylight Savings Time bug?  
      > It does! If you open Calendar on your iOS 7 device, you will notice that while the time of your operating system is set correctly, the line marking the time in Calendar is an hour old.

      > 訳: Appleは2010年、2011年、2012年にサマータイムに切り替えた後に発生するバグを起こしたばかりか、似たような失敗を2013年の新年にDo Not Disturb機能でやらかした。そして今は2014年、iOS 7はサマータイムのバグを含んでいるだろうか？  
      > 含んでいた！カレンダーのアプリをiOS 7の端末で開くと、OSの時刻は正しく設定されているのに、カレンダーのアプリが指している現在時刻の線が1時間古い時刻を指しているのに気づくだろう。

        - 訳注: iOSはiPhoneやiPadで使用されているOS（基本ソフト）です。iPhoneやiPadに限らず、正しく対応しない限り、サマータイムの切り替え前後にスマートフォンのアラームが動作しない、間違った時刻を表示することになってしまいます。そして正しく対応できなかった事例は、長年サマータイムを経験しているであろうAppleが作ったiPhoneにさえも何度も何度も発生しています。
    - [Glitch in Google Calendar - Daylight Savings Time March 11, 2018 - Google プロダクト フォーラム](https://productforums.google.com/forum/#!msg/calendar/2vrV8zKirOI/AeFdUfwOAgAJ)  
      > Any events & times entered on the calendar after March 11, 2018, Daylight Savings Time, are displaying the time 1 hour earlier than what I entered.  
      > 訳: 2018年3月11日、サマータイム（の開始日）以降のあらゆるイベントや時刻が、私が入力したよりも1時間早く表示されている。
        - 訳注: Googleサイトというホームページ作成サービスで作成したホームページにGoogle Calendarを表示するよう設定すると、Google Calendar上では正しい時刻で表示されているにもかかわらず、Googleサイトで作成したホームページ上で見ると1時間早く表示されてしまう、というバグ。
    - [1233809 - Daylight Savings Time Displays the Wrong Date in JavaScript on Windows](https://bugzilla.mozilla.org/show_bug.cgi?id=1233809)  
      > March 10 1980 is shown as GMT -04:00 for Firefox on Windows while Firefox on Unix systems display GMT -05:00.  This bug effects all versions of Firefox.  Tested on Windows 7, 8.1 & 10.  
      > ...  
      > This is likely related to the 2005 change to the U.S.
      > 訳: WindowsのFirefoxで1980年3月10（の時刻）がGMO -04:00として表示されているが、UnixのシステムではGMO -05:00として表示されている。このバグはすべてのバージョンのFirefoxが影響を受けている。Windows 7, 8.1, 10でテストした。  
      > ...（訳者による中略）...  
      > これはおそらく2005年における合衆国のサマータイムの変更が関係している。
        - 訳注: Windows版Firefoxで、東部標準時における、過去の夏時間の開始時期が正しく反映されていないというバグ。  
          このように、夏時間への切り替え時の問題は、実際に切り替える時だけでなく、切り替えがあった年以降においても、過去の時刻を扱うソフトウェアや、その他の過去の記録を扱う場合においても、間違いの元になることがあります。  
          つまり、一度サマータイムを採用してしまうと、**採用した年以降にも混乱を招く恐れがある**のです。

### 身体への影響や、結果として起こる問題

- cyberloafing（勤務中のインターネットの私用）が増える
    - [Lost sleep and cyberloafing: Evidence from the laboratory and a daylight saving time quasi-experiment.](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fa0027557)
        - > We also demonstrate that the shift to Daylight Saving Time (DST) results in a dramatic increase in cyberloafing behavior at the national level.
        - > 訳: サマータイムへの切り替えが、勤務中のインターネットの私用を国レベルで劇的に増やす、ということを示した。
- [The Human Circadian Clock's Seasonal Adjustment Is Disrupted by Daylight Saving Time - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0960982207020866)


### サマータイムを採用している国における事情

- EU全体で夏時間を廃止しようとする動き
    - [Daylight saving time may become a thing of the past in Europe](https://www.nbcnews.com/news/world/daylight-saving-time-may-become-thing-past-europe-n893131)
        - 要約: [中央ヨーロッパ時間](https://ja.wikipedia.org/wiki/%E4%B8%AD%E5%A4%AE%E3%83%A8%E3%83%BC%E3%83%AD%E3%83%83%E3%83%91%E5%A4%8F%E6%99%82%E9%96%93)に属するフィンランドでは、夏は白夜のため、サマータイムであろうとなかろうと一日中日が昇っている。そのためサマータイムの恩恵を享受できない。どころか、時計をずらすことによる健康被害がある分、デメリットの方が大きい。そのためEUの議会に掛け合って、サマータイムを廃止するよう求めている。  
          EUのルール上、加盟国全体で夏時間の切り替えタイミングを設定しているため、EU全体で夏時間を廃止するという動きになっている。
- ドイツにおける夏時間についての2つの調査
    - [ドイツマスコミスキャン～サマータイムなんかいらない（上）－JanJanニュース](https://web.archive.org/web/20110202152620/http://www.news.janjan.jp/media/0804/0804064352/1.php)
        - > 実は、夏時間制度に慣れているはずのドイツ人でも、切り換え時に時計の針を１時間進めるのか、それとも戻すのかで悩んでしまう人がどうも結構いるらしいのである。  
          > 市場調査機関のＩＰＳＯＳが１４歳以上の男女５００人を対象に行った調査（先月１９、２０日に実施）によると、正解を言えなかった人が３人に１人の割合でいたという。
        - > 【１９８０年からドイツでは夏時間が導入されています。いつ時計の針を進めるのか、あるいは戻すのか覚えていられない人たちにとっては腹立たしい制度です。また、夏時間導入の目的――エネルギーの節約――はそもそも達成されるのかという点も議論になっています。意見をお聞かせください。夏時間は廃止すべきだと思いますか】  
          > 何やら誘導的な質問であるような気もしないでもないが、結果は以下のとおり：  
          > ・夏時間は維持すべきである……………３０.６％  
          > ・夏時間は廃止すべきである……………６６.０％  
          > ・わからない（どっちでもいい）………　３.３％  
          > （投票総数は１４,００３、４月６日現在）

### その他、サマータイムの導入に伴い想定される、\*\*悪い\*\*影響

- オリンピックの競技を含めた、夕方の活動時が却って暑い自国の活動となってしまう。
    - [【電子版】政府、夏時間検討へ　慎重姿勢から一転　首相が前向き姿勢 | 政治・経済 ニュース | 日刊工業新聞 電子版](https://www.nikkan.co.jp/articles/view/00483784)
      > 仮に2時間繰り上げる夏時間を導入すれば、（中略）一方で、夕方の競技が暑い時間帯に行われるジレンマも抱える。



## サマータイムの良い側面について


## サマータイムのよい影響と悪い影響両方の紹介

- サマータイム開始時に交通時刻が増え、終了時に減る
    - [Daylight Savings Time and Traffic Accidents | NEJM](https://www.nejm.org/doi/full/10.1056/nejm199604043341416)
        - > The loss of merely one hour of sleep can increase the risk of traffic accidents. It is likely that the effects are due to sleep loss rather than a nonspecific disruption in circadian rhythm, since gaining an additional hour of sleep at the fall time shift seems to decrease the risk of accidents.
        - > 訳: たった1時間の睡眠不足が交通事故のリスクを増やしうる。これは体内時計の小さな乱れというよりは、睡眠不足によるものだろう。フォールタイムへの移行（サマータイムの終了）が、交通事故のリスクを減らすらしいからである。

<!--

### Daylight savings time bug? | Adobe Community

Title                                  | URL
---------------------------------------|-----------
daylight saving time - Google Scholar | https://scholar.google.co.jp/scholar?start=0&q=daylight+saving+time+&hl=ja&lr=lang_en%7Clang_ja&num=20&as_sdt=0,5
daylight savings time bug - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time+bug&rlz=1C1GCEA_enJP787JP787&ei=2wxpW-PwKsry8QXn3auQCA&start=10&sa=N&biw=1240&bih=802
daylight savings time - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time&rlz=1C1GCEA_enJP787JP787&source=lnms&tbm=nws&sa=X&ved=0ahUKEwiG_4jd_NncAhVIu7wKHcbQAH0Q_AUICigB&biw=1240&bih=1294&dpr=1.5
日本に『サマータイム制』はいらない！ ( 夏 ) - 気象・歳時・防災 コラム - Yahoo!ブログ | https://blogs.yahoo.co.jp/otenki_bosai/47260331.html
Daylight Savings Time Bug Xerox | http://fieryforums.efi.com/showthread.php/5105-Daylight-Savings-Time-Bug-Xerox
Why would daylight-saving time mess up my computer? - HowStuffWorks | https://computer.howstuffworks.com/dst-bug.htm
Daylight savings time bug (beta forum topic continued here) - 2BrightSparks | https://www.2brightsparks.com/bb/viewtopic.php?t=11184
Daylight savings time bug? - Adobe Community | https://forums.adobe.com/thread/813805
Remember The Milk - Forums / Help / Daylight Savings Time Bug in Android | https://www.rememberthemilk.com/forums/help/12344/
March 11 calendar bug - Outlook Mac | https://social.technet.microsoft.com/Forums/office/en-US/a43a6c67-7d02-4a62-95e5-5ff931f8f7ac/march-11-calendar-bug-outlook-mac?forum=outlook
daylight savings time trouble - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time+trouble&rlz=1C1GCEA_enJP787JP787&oq=daylight+savings+time+trouble&aqs=chrome..69i57j0.12334j0j7&sourceid=chrome&ie=UTF-8
Is daylight saving time worth the trouble? Research says no | http://theconversation.com/is-daylight-saving-time-worth-the-trouble-research-says-no-86739
Why daylight saving time can be bad for your health - CNN | https://edition.cnn.com/2016/03/11/health/daylight-saving-time-health-effects/index.html
404 Blog Not Found:夏時間を支持するのは頭が春な人だけ | http://blog.livedoor.jp/dankogai/archives/51239059.html

https://www.ncbi.nlm.nih.gov/pubmed/11152980


https://twitter.com/kiyomimi/status/1026966474231963648
-->
