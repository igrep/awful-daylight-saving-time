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

### 身体への影響


### 外国における廃止に向けた動き

- EU全体で夏時間を廃止しようとする動き
    - [Daylight saving time may become a thing of the past in Europe](https://www.nbcnews.com/news/world/daylight-saving-time-may-become-thing-past-europe-n893131)
        - 要約: [中央ヨーロッパ時間](https://ja.wikipedia.org/wiki/%E4%B8%AD%E5%A4%AE%E3%83%A8%E3%83%BC%E3%83%AD%E3%83%83%E3%83%91%E5%A4%8F%E6%99%82%E9%96%93)に属するフィンランドでは、夏は白夜のため、サマータイムであろうとなかろうと一日中日が昇っている。そのためサマータイムの恩恵を享受できない。どころか、時計をずらすことによる健康被害がある分、デメリットの方が大きい。そのためEUの議会に掛け合って、サマータイムを廃止するよう求めている。  
          EUのルール上、加盟国全体で夏時間の切り替えタイミングを設定しているため、EU全体で夏時間を廃止するという動きになっている。

### その他、サマータイムの導入に伴い想定される、\*\*悪い\*\*影響

- オリンピックの競技を含めた、夕方の活動時が却って暑い自国の活動となってしまう。
    - [【電子版】政府、夏時間検討へ　慎重姿勢から一転　首相が前向き姿勢 | 政治・経済 ニュース | 日刊工業新聞 電子版](https://www.nikkan.co.jp/articles/view/00483784)
      > 仮に2時間繰り上げる夏時間を導入すれば、（中略）一方で、夕方の競技が暑い時間帯に行われるジレンマも抱える。



## サマータイムの良い側面について



<!--

### Daylight savings time bug? | Adobe Community

Title                                  | URL
---------------------------------------|-----------
daylight saving time - Google Scholar | https://scholar.google.co.jp/scholar?start=0&q=daylight+saving+time+&hl=ja&lr=lang_en%7Clang_ja&num=20&as_sdt=0,5
daylight savings time bug - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time+bug&rlz=1C1GCEA_enJP787JP787&ei=2wxpW-PwKsry8QXn3auQCA&start=10&sa=N&biw=1240&bih=802
daylight savings time - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time&rlz=1C1GCEA_enJP787JP787&source=lnms&tbm=nws&sa=X&ved=0ahUKEwiG_4jd_NncAhVIu7wKHcbQAH0Q_AUICigB&biw=1240&bih=1294&dpr=1.5
Glitch in Google Calendar - Daylight Savings Time March 11, 2018 - Google プロダクト フォーラム | https://productforums.google.com/forum/#!msg/calendar/2vrV8zKirOI/AeFdUfwOAgAJ
1233809 - Daylight Savings Time Displays the Wrong Date in JavaScript on Windows | https://bugzilla.mozilla.org/show_bug.cgi?id=1233809
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
