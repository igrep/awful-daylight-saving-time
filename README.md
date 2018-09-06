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
収集する情報については、できるだけ「**過去に実際にあったこと、あるいは実際に起こる可能性が高いと予想されるもの**」を中心に収集します。

GitHubに公開していることから察せられるとおり、Pull requestやIssue報告による情報提供は強く歓迎します。

### 追記

こちらの記事曰く、サマータイムは東京オリンピックの時期限定での導入ではなく、恒久的な導入を検討しているようです。

[東京五輪終わっても「サマータイム」恒久的運用へ　議員立法による成立を目指す : スポーツ報知](https://www.hochi.co.jp/topics/20180808-OHT1T50025.html)

> 自民党幹部によると、秋の臨時国会で制度・設計に向けた議論を行い、議員立法による成立を目指す。当初は夏時間を１９、２０年に限る案も浮上していたが、その都度、必要になるＩＴ関係のシステム変更に伴う負担などが大きいとして、東京五輪後も恒久的な制度とする方針。野党とも合意を取りながら、議論を進めていくとしている。

「2年間限定の導入は無茶だ」という主張は、この方針によって無効化される可能性が高いので、ご注意ください。

### ここでいう「サマータイム」について

過去、北海道庁において、「一部の職員が通常の勤務時間より１時間早出出勤する」政策を、「サマータイム」と称して行ったようです。

[サマータイム実施結果 ｜ 総合政策部政策局参事](http://www.pref.hokkaido.lg.jp/ss/ssa/summertime_jissikekka.htm)

紛らわしさを防止するためにあらかじめ述べておきますと、ここで扱う「サマータイム」は、あくまでも対象の地域で使用する時刻を繰り上げることを指しており、北海道庁で行ったような、労働時間をはじめとする各種のイベントの実施時間を繰り上げる「サマータイム」ではありません。

## サマータイムの悪い側面について

### 省エネ効果が実際にはないこと

- [Effect of daylight saving time on lighting energy use: A literature review - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0301421507002273)
    - > This paper presents a literature review concerning the effects of DST on energy use. Simple estimates suggest a reduction in national electricity use of around 0.5%, as a result of residential lighting reduction. Several studies have demonstrated effects of this size based on more complex simulations or on measured data. However, there are just as many studies that suggest no effect, and some studies suggest overall energy penalties, particularly if gasoline consumption is accounted for. There is general consensus that DST does contribute to an evening reduction in peak demand for electricity, though this may be offset by an increase in the morning.
    - > 訳: 本稿では、エネルギーの使用についてのサマータイムの影響に関する文献の調査を行った。単純な試算では、住宅における照明の使用が減ることにより、電力消費量が約0.5%減ることが示されている。より複雑なシミュレーションや実測値に基づき、この減少量を示した研究もある。しかしながら、同時に効果はないとする研究も多く、ガソリンの消費量を考慮すると、全体としてはエネルギーのペナルティーになっているとする研究もある一般的には、サマータイムは夕方における電力需要のピークの減少には貢献しているものの、朝における増加によって相殺してしまう、という認識がある。
- [Does Daylight Saving Time Save Energy? Evidence from a Natural Experiment in Indiana](https://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00131)
    - > Our main finding is that, contrary to the policy's intent, DST increases electricity demand. The findings are consistent with simulation results that identify a trade-off between reducing demand for lighting and increasing demand for heating and cooling. We estimate a cost to Indiana households of $9 million per year in increased electricity bills. We also estimate social costs of increased pollution emissions between $1.7 to $5.5 million per year.
    - > 訳: 政策の意図に反して、サマータイムは電力の需要を増加させていることがわかった。明かりに対する需要を減らす一方冷暖房の需要を増やす、というシミュレーション結果ともこの結果は一貫している。汚染物質の排出が増加することによる社会的なコストは、1年辺り1.7百万ドルから5.5百万ドルであると我々は推定した。
- [今夏（2011年夏）の節電に向けて ｜ 産総研：安全科学研究部門– 持続可能な社会実現に向けた評価研究部門 | 産総研 AIST RISS](https://www.aist-riss.jp/column/2341/)
    - > 生活スケジュールの変化（サマータイムの導入）  
      > 結論: 有効性が低い（節電効果を期待するには6時間程度の時間シフトが必要）  
      > ピーク電力需要時間帯は9時～20時であるため、この時間帯を外すような大規模な時間シフトでないと節電効果は期待できません。すなわち、節電対策のためにサマータイムを導入する場合、1時間程度のシフトではなく、6時間程度のシフトが必要になります。
- [計画停電と空調節電対策（速報）(9): 行動の変化（サマータイムなど） ｜ 産総研：安全科学研究部門– 持続可能な社会実現に向けた評価研究部門 | 産総研 AIST RISS](https://www.aist-riss.jp/column/29731/)
    - > 生活スケジュールの1時間前倒し（いわゆるサマータイム）は、夕方に事務所の空調を若干削減するものの、家庭の空調を大幅に増加させるため、逆効果となる可能性があることが分かりました。
- [サマータイム—健康に与える影響 一般社団法人 日本睡眠学会 サマータイム制度に関する特別委員会](http://www.jssr.jp/data/pdf/summertime_20120315.pdf)
    - > 省エネ効果ですが、4ページですでに述べたように、ロシア、フランスでは否定されています。2000年のオリンピック開催に合わせてサマータイムを延長したオーストラリアの2州でも、延長によって夕方の電力消費量は節約できたのですが、朝の電力消費量は増加し、全体として省エネ効果はありませんでした。米国・インディアナ州では、2007年のサマータイム導入時に家庭の電力消費量が1～4％増加したようです。照明の電力消費量は減少したものの、冷暖房の使用がそれ以上に増加したためです。
    - 注: おそらくこの節の冒頭に挙げた、[Does Daylight Saving Time Save Energy? Evidence from a Natural Experiment in Indiana](https://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00131)のことと思われる。
- [Does Daylight Savings Time Save Energy? Evidence from Ontario | SpringerLink](https://link.springer.com/article/10.1007/s10640-017-0131-x)
    - > The results suggest that daylight savings time reduces the demand for electricity by about 1.5% in Ontario. The reductions in electricity consumption is concentrated during the evening period. The reduction in electricity demand appears to persist for at least several weeks following the transition to daylight savings time.
    - > 訳: オンタリオにおける電力需要の減少は1.5%程度であるということが示された。電力需要の減少は夕方の時間帯に集中し、電力需要の減少は、サマータイムへの切り替えから少なくとも数週間持続するようだ。

<!--
https://web.a.ebscohost.com/abstract?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=01956574&AN=128030841&h=xXKIeb4%2b5QyKC1%2fQvg3gvsa3EeC8SsLsNUAUqSwVz%2bvrZL0S6sJ88njfpZvNH2B0wRlWzpHZFFK0nLJcSOYiCQ%3d%3d&crl=c&resultNs=AdminWebAuth&resultLocal=ErrCrlNotAuth&crlhashurl=login.aspx%3fdirect%3dtrue%26profile%3dehost%26scope%3dsite%26authtype%3dcrawler%26jrnl%3d01956574%26AN%3d128030841
-->

### システム修正に関わる問題（過去発生したバグ、障害など）

- [サマータイムのシステム対応が到底間に合わない理由 ITインフラへの影響を議論するシンポジウムで問題提起(1/5) | JBpress(日本ビジネスプレス)](http://jbpress.ismedia.jp/articles/-/54002)
    - > もちろん、システムへの影響は、どのような運用を行うかでも大きく異なる。ただし、それを議論して運用方法を決めるだけでも時間がかかる。仮にルールをきちんと作ったとしても、解釈の誤りや実装漏れを完全に防ぐことはできず、いろいろなところに問題が起こる可能性はある。
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
- サマータイム開始時に存在しない時刻ができたり、終了時に同じ時刻が2回存在するため、正しく動作しないシステムが多数存在しうる
    - [サマータイム導入が難しい理由、迫られる「2度訪れる同時刻」への対応 - BCN＋R](https://www.bcnretail.com/market/detail/20180812_81432.html)
        - > 通常時間からサマータイムに移行する際は、時計の針を進める。サマータイム実施国のほとんどは、この変更を深夜の午前1～3時に行っている。ここでは米国にならい、サマータイム開始日の午前2時に時計を進めるとしてみよう。2時間のシフトを行うとすれば、開始日の1時59分59秒の次は、4時00分00秒になる。つまり、1年のうちサマータイム開始日に限り、2時台・3時台は存在しない時刻という扱いになる。翌日の営業開始までの時間が2時間失われることで、夜間の業務を完了するための時間が足りなくなる可能性がある。
        - > サマータイム終了日には逆に、時計の針を2時間戻す。このため、未明の3時59分59秒の次は、もう一度2時00分00秒に戻る。つまりこの日に限っては、2時台・3時台の時刻は2回存在する。この2時間の間に発生した出来事を記録するには、「○月×日サマータイム午前2時35分」「○月×日通常時間午前2時35分」などと区別しておかないと、時刻を特定することができなくなってしまう。
        - > サマータイムを想定していないシステムでこれを扱うとどうなるか。例えば、3時間の実行継続を想定して「1時30分開始・4時30分終了」と設定した処理があった場合、サマータイム開始日にはこの処理が1時間で終わってしまう可能性がある。同じ処理がサマータイム終了日に予定されていた場合は、処理が5時間継続してしまうおそれがある。
- 電波時計が正しく機能するか不透明である、あるいはGPS電波時計の設定を手で修正する必要がある
    - [サマータイム導入で「電波時計が狂う」？　メーカーに聞いた - ITmedia NEWS](http://www.itmedia.co.jp/news/articles/1808/09/news094.html)
        - > そもそも「（この方法は）告示などで正式に決まっておらず、標準電波をどのような形で送信するかも決まっていない」と、NICTは説明しています。「電波時計の時刻合わせ機能が引き続き使用可能かは現時点では全く不明です」
        - > しかし、世界各国のサマータイムは「1時間繰り上げる」ことが一般的なので、カシオ計算機の製品は「サマータイムがオン」という情報を受け取っても「1時間繰り上げられている」として反映させる設定になっています。そのため、政府が検討しているという「2時間の繰り上げ」の場合、ワールドタイムを1時間分しか補正してくれず、残りの1時間分、ずれが生じるといいます。
        - > 電波時計にはもう1つ、GPS（全地球測位システム）情報に基づき、現在位置のタイムゾーンに合わせて時刻を表示するタイプのものがあります。受信端末（時計）側で設定したタイムゾーンに応じて時刻を表示します。  
          > そのため、政府が検討しているという「2時間の繰り上げ」の場合、現在の日本標準時より2時間ずれたタイムゾーンを設定すれば、サマータイムの影響は出ないことになります。
- その他のサマータイムへの切り替え時におけるシステムの不具合
    - [Daylight Savings Time Bug Xerox](http://fieryforums.efi.com/showthread.php/5105-Daylight-Savings-Time-Bug-Xerox)
        - > Every time the clocks change we get a significant slowdown in the performance of the print driver. The slowdown occurs when opening the printer properties UI and is also slower when pressing print and waiting for the application to return to other tasks.
        - > 訳: 時計を切り替える際、いつもプリンタードライバーの動作が明らかに遅くなる。速度の低下はプリンターのプロパティを開くときに見られ、加えて「印刷」ボタンを押してからほかのタスクに返ってくるまでも遅い。
    - [Daylight savings time bug? - Adobe Community](https://forums.adobe.com/thread/813805)
        - > I woke up this morning to find 3 of my sites all encountering a variation of this error:  
            > Date value passed to date function createDateTime is either unspecified or invalid. Specify a valid date in createDateTime function.  
            > Hour '2' specified in {ts '2011-3-13 2:0:0'} does not exist in the timezone Eastern Standard Time, if Daylight Saving Time is enabled.  
            Today is the first day of daylight savings time, and the code affected hasn't been altered in years. Is anyone else encountering this error? Any idea how to fix?
        - > 訳: 今朝起きたら、私の3つのサイトすべてでこんな種類のエラーが発生していたことに気づいたんだ:  
            > createDateTime関数に渡された日付の値が示されなかった、あるいは不正でした。正常な日付をcreateDateTime関数に示してください。  
            > サマータイムが有効な場合、{ts '2011-3-13 2:0:0'} に示した時間 '2' は東部標準時間では存在しません。  
            今日はサマータイムの最初の日で、影響を受けたコードは何年間も修正されていない。誰かこのエラーに出会っていないだろうか？何か修正する方法はある？
        - 訳注: おそらく、報告者が作成したアプリケーションが東部標準時間で動作するにも関わらず、入力される日時にタイムゾーンの情報が含まれていなかったことが原因の模様。  
            「影響を受けたコードは何年間も修正されていない」ことから察せられるとおり、サマータイムに正しく対応していないことによる問題は、関係者が忘れた頃に問題を出すことがある、という例として掲載した。

### 身体への影響や、結果として起こる問題

- 睡眠不足
    - [サマータイム—健康に与える影響 一般社団法人 日本睡眠学会 サマータイム制度に関する特別委員会](http://www.jssr.jp/data/pdf/summertime_20120315.pdf)
        - > これらからわかることは、ヒトが夏時間に適応するには従来考えられていた以上に時間がかかる、ということです。では、その原因はどこにあるのでしょうか？私たちは体内時計と社会生活のスケジュールとの間に生じる1時間のズレ（脱同調）に原因があるのではないかと考えています。つまり、体内時計で定められた起床就寝時刻と、実際に行わなければならない起床就寝時刻とが乖離（かいり）してしまうことが問題なのではないか、ということです。体内時計で決められた時刻にとる眠りは自然で質も高いのですが、社会生活のスケジュールに無理矢理合わせた眠りは質が悪くなる可能性があります。
- 交通事故の増加
    - [Excess Risk of Fatal Road Traffic Accidents on the Day of Da... : Epidemiology](https://journals.lww.com/epidem/Fulltext/2018/09000/Excess_Risk_of_Fatal_Road_Traffic_Accidents_on_the.25.aspx)
        - > Our findings suggest that, on average, DST changes are associated with a cost of 1.5 lives every year due to road traffic accidents in Spain’s capital cities. Considering that 78% of deaths from road traffic accidents in Spain occur on roads outside of cities, this could have an additional cost of another 5 lives every year.
        - > 訳: 平均して、サマータイムへの切り替えは、スペインの主要な都市における年間1.5人の交通事故死と関連付けられていることがわかった。スペインにおける交通事故の78%の交通事故死が主要都市以外の道路で発生していることを考慮すると、さらに年間5人の死亡を発生させていた可能性もある。
    - [Spring Forward at Your Own Risk: Daylight Saving Time and Fatal Vehicle Crashes](https://www.aeaweb.org/articles?id=10.1257/app.20140100)
        - > My results imply that from 2002-2011 the transition into DST caused over 30 deaths at a social cost of $275 million annually. Employing four tests to decompose the aggregate effect into an ambient light or sleep mechanism, I find that shifting ambient light only reallocates fatalities within a day, while sleep deprivation caused by the spring transition increases risk.
        - > 2002年から2011年におけるサマータイムへの切り替え時、1日で30人以上の死者が出て、年間275百万ドルの社会的なコストがかかったことを示している。4つのテストで合計された結果を環境光の変化や睡眠のメカニズムといった要因に分解することで、環境光の変化は1日に発生する死亡事故を移し替えているだけに過ぎず、夏時間の開始による睡眠不足がリスクを増加させている、ということを発見した。
- cyberloafing（勤務中のインターネットの私用）が増える
    - [Lost sleep and cyberloafing: Evidence from the laboratory and a daylight saving time quasi-experiment.](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fa0027557)
        - > We also demonstrate that the shift to Daylight Saving Time (DST) results in a dramatic increase in cyberloafing behavior at the national level.
        - > 訳: サマータイムへの切り替えが、勤務中のインターネットの私用を国レベルで劇的に増やす、ということを示した。
- 心筋梗塞の増加
    - [オリンピックでサマータイム？　心筋梗塞増やす可能性も：朝日新聞デジタル](https://www.asahi.com/articles/SDI201808108087.html)
        - > 悪影響は、単に「昼間眠くなる」とかに限らず、心筋梗塞のリスクが上がるのだそうです。私も自分で論文を調べてみましたが、確かに、サマータイム（"Daylight Saving Time"）と心筋梗塞の発症の関連を示した 報告が複数あります。2012年以降もサマータイムが心筋梗塞の発症リスクを増やすことを示す研究が発表されています。クロアチアでは3月の最後の日曜日からはじまって、10月の最後の日曜日で終わるのですが、2412人の急性心筋梗塞患者を解析した結果、3月のサマータイム開始後の最初の平日の4日間では心筋梗塞の発症が1.29倍に、10月のサマータイム終了後では1.44倍になることが示されました。
- 子供をはじめとする生活リズムの乱れ
    - [きよ耳さんのツイート: "は？待って？サマータイム冷静に考えてみたらさ、導入されたらスーパー規則正しく生きてる幼児を2時間早く叩き起こし保育園に連れていき、2時間早く寝かせるんでしょ？いやーー簡単に言ってくれるわーーー🔪🔪仕事になんねぇな。"](https://twitter.com/kiyomimi/status/1026966474231963648)
- [The Human Circadian Clock's Seasonal Adjustment Is Disrupted by Daylight Saving Time - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0960982207020866)

### 食品業界への悪影響

- 時間単位で消費期限を管理しているスーパーやコンビニが、混乱する可能性がある
    - [「サマータイムやめて」　食品流通業界、実施案に悲鳴（食品新聞） - Yahoo!ニュース](https://headlines.yahoo.co.jp/hl?a=20180829-00010000-shokuhin-bus_all)
        - > なお、新日本スーパーマーケット協会は当該文書の中で「サマータイム移行日に期限を『×月×日××時』と定めている食品の安全性を確保できない」とするなど、足の早い消費期限商品で起こり得る食品事故の可能性にも言及している。
    - [「サマータイムやめて」スーパーとコンビニの悲鳴の裏側(井出留美) - 個人 - Yahoo!ニュース](https://news.yahoo.co.jp/byline/iderumi/20180830-00094991/)
        - > サマータイムを導入し、時計の針を1～2時間進めるということは、全国で、時間単位で管理しているデイリー食品の設定を、オリンピック・パラリンピックの時期だけ変えて、また後に戻すということだ。設定の変更にどれだけの労力と手間がかかるのか、そして混乱が起きるのか。
- 生鮮食品や惣菜の需要予測が難しくなり、食品ロスが増える恐れがある
    - [全国スーパーマーケット協会さんのツイート: "記事では期限表示の件を取り上げていただいてますが、時間のズレにより来店時間の気候もずれ、生鮮・惣菜の製造や値引きのタイミングが難しくなり食品ロス増加も懸念されます。 ／　夏時間 コンビニ悲鳴の裏側 | 2018/8/30(木) - Yahoo!ニュース https://t.co/ODwBwn1iKo @YahooNewsTopics"](https://twitter.com/newsuper_jp/status/1034982296963756032)

### サマータイムを採用している国における事情

- EU全体で夏時間を廃止しようとする動き
    - [European Commission - PRESS RELEASES - Press release - Summertime Consultation: 84% want Europe to stop changing the clock](http://europa.eu/rapid/press-release_IP-18-5302_en.htm)
        - > **The European Commission has today published the preliminary results of the public consultation on clock change in Europe.**
        - > This online consultation, which ran from 4 July to 16 August 2018, received 4.6 million responses from all 28 Member States, the highest number of responses ever received in any Commission public consultation. According to the preliminary results (see annex), 84% of respondents are in favour of putting an end to the bi-annual clock change.
        - > **Next steps**
        - > The final results of the public consultation will be published in the coming weeks. The Commission will now make a proposal to the European Parliament and the Council with a view of changing the current clock change arrangements.
        - > 訳: **ヨーロッパ委員会は、本日、ヨーロッパにおける時刻の変更についての公開調査の事前結果を公開した。**
        - > このオンラインでの調査は7月4日から8月16日にかけて行われ、ヨーロッパ委員会によるこれまでの公開調査の中で最も多い、4.6百万の回答を28の加盟国から得た。事前の結果（付録を見よ）によると、84%もの回答者が、年2回行われる時刻の変更（訳注: つまりサマータイムのこと）を終了させることに賛成であるという。
        - > **次のステップ**
        - > 公開調査の最終的な結果は、数週間後に公開されるだろう。これより委員会はヨーロッパ議会と理事会に対し、時刻の変更に向けた準備をするという見解を提出する。
    - [サマータイム見直し、欧州検討　パブコメ投票４６０万人：朝日新聞デジタル](https://www.asahi.com/articles/ASL8H4SQLL8HUHBI01C.html)
        - > 既に実施している「本家」の欧米では見直しの動きが広がっている。「健康によくない」「省エネの効果が乏しい」などの指摘が出ているためだ。欧州連合（ＥＵ）では１６日まで域内市民に対する「パブリックコメント」があり、１カ月余で４６０万人以上が賛否を寄せた。
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
    - [東京新聞:サマータイム「無理」　夕方予定競技が酷暑に:社会(TOKYO Web)](http://www.tokyo-np.co.jp/article/national/list/201808/CK2018083002000126.html)
        - > 　サッカーとラグビーは午後二時半。馬術は同三時－。時間が二時間繰り上がった場合の開始時刻だ。「夕方開始」が「昼すぎ開始」と早まることで、気温が二度程度上昇することが見込まれ、熱中症の危険にさらされる。屋外開催の可能性があるアーチェリーとスポーツクライミング、バスケットボール三人制も同二時台のスタートとなる。
        - > 　馬は人よりも暑さに弱いとされる。日本馬術連盟の木口明信常務理事は「決まっている『午後五時』より暑い時間帯の開催は無理」と断言。「組織委からの問い合わせは一度もない。各競技の特殊性を聞かずに話を進めるのはおかしい」と不信感を口にした。
    - [【電子版】政府、夏時間検討へ　慎重姿勢から一転　首相が前向き姿勢 | 政治・経済 ニュース | 日刊工業新聞 電子版](https://www.nikkan.co.jp/articles/view/00483784)
      > 仮に2時間繰り上げる夏時間を導入すれば、（中略）一方で、夕方の競技が暑い時間帯に行われるジレンマも抱える。
- 国際オリンピック委員会が決めた競技時間を変えることにより、放映権を持った放送局の意向に背くことになる
    - [東京新聞:サマータイム「無理」　夕方予定競技が酷暑に:社会(TOKYO Web)](http://www.tokyo-np.co.jp/article/national/list/201808/CK2018083002000126.html)
        - > 　サマータイムは、導入済みの欧米で健康被害が報告されるなど問題点が既に指摘されているが、そもそも、国際オリンピック委員会が決めた競技時間を実質二時間早めるような変更が可能なのか。東京五輪の放映権は米テレビＮＢＣが持ち、日程や時間の決定に関与したとされる。
        - 　米国スポーツに詳しい元プロ野球楽天ゼネラルマネジャーのマーティ・キーナートさんは「望ましい時間に放送できなくなれば、ＮＢＣが再変更を求めてくるかもしれない」と危ぶむ。

### 新聞各社の主張

※「過去に実際にあったこと、あるいは実際に起こる可能性が高いと予想されるもの」という趣旨からそれますが、影響力が高そうなので載せておきます。

- [社説：サマータイム議論　「五輪のため」は短兵急だ - 毎日新聞](https://mainichi.jp/articles/20180810/ddm/005/070/021000c)
    - > 競技日程には、巨額の放映権料を支払っている米国メディアの意向が反映されている。夏時間を導入すれば、当初の日程とずれが生じる。米国との調整は図れるのか。
    - > 大会運営全体を考えての提案なのか疑問が拭えない。
    - > 夏時間制度は国民生活に大きく影響する施策だ。五輪・パラリンピックだけの問題ではない。にもかかわらず、「スポーツの祭典」を錦の御旗（みはた）に、２年足らずのうちに実行しようというのは、短兵急に過ぎないか。
- [（社説）サマータイム　あまりに乱暴な提案だ：朝日新聞デジタル](https://www.asahi.com/articles/DA3S13633094.html)
    - > 日本で約１０年前に導入が検討された時は、家庭用の照明需要などが減るとの試算もあった。だが、炭素排出量全体と比べれば効果はかなり小さかった。他の不利益を上回る利点があるのか、社会や技術の変化も踏まえて、改めて見極めるべきだ。
- [社説：サマータイム　導入の利点が見えない : 京都新聞](https://www.kyoto-np.co.jp/politics/article/20180809000045)
    - > こうしたマイナス面は、以前から繰り返し指摘されてきた。課題の検証もなく安易に導入を提案する姿勢からは、五輪のためなら社会のコスト増を招いても許されるという無神経さも感じられる。
    - > サマータイムを導入しても気温は下がらない。五輪の暑さ対策にはなお知恵を絞るべきだ。それをせずして国民生活に負担をかけるなら本末転倒というしかない。
- [サマータイム　国民生活への影響考慮を | 社説 | コラム | 熊本日日新聞社](https://kumanichi.com/column/syasetsu/590447/)
    - > 導入国は、高緯度で夏と冬の日照時間の差が大きい欧米に多い。日本など中、低緯度の国では、そもそも欧米ほどの利点はないとされる。その欧米にも反対論があり、欧州連合（ＥＵ）は廃止の是非を検討している。
    - > さまざまな弊害が生じる可能性を抱えてまで、サマータイムを導入するメリットがあるのだろうか。政府、与党内にも慎重論が根強くあるという。五輪成功という大義名分だけで安易に飛び付いてはなるまい。国民生活への影響を十分考慮し、導入には慎重な検討が必要だ。
- [【主張】サマータイム　混乱回避が導入の条件だ - 産経ニュース](https://www.sankei.com/column/news/180809/clm1808090002-n1.html)
    - > 日本は戦後の占領期にエネルギー消費の抑制をねらって導入したが、国民の理解が得られずに中止した経緯がある。韓国も１９８８年のソウル五輪に合わせて導入したが「労働時間が長くなった」などとして撤回した。こうした過去の事例も検証してもらいたい。
    - > サマータイムは過去に何度も浮上しては消えていった。五輪に向けて導入しても混乱が生じては元も子もない。拙速は厳に慎むべきである。
- [サマータイム　効果と弊害の慎重な見極めを : 社説 : 読売新聞（YOMIURI ONLINE）](https://www.yomiuri.co.jp/editorial/20180818-OYT1T50107.html)
    - > そもそも夏時間は、夏の日照時間が極めて長い高緯度の国に適した制度だ。ほぼ中緯度に位置する日本で、どれほどのメリットがあるのか不透明とされる。
    - > 夏時間を長年採用してきた欧州でさえ、見直しの機運が出ている。欧州連合（ＥＵ）は「体内時計が狂って体調を崩す恐れがある」など、睡眠や健康への悪影響を理由に存廃の検討を始めた。こうした海外の動向も参考にしたい。

## サマータイムの良い側面について


## サマータイムのよい影響と悪い影響両方の紹介

- サマータイム開始時に交通時刻が増え、終了時に減る
    - [Daylight Savings Time and Traffic Accidents | NEJM](https://www.nejm.org/doi/full/10.1056/nejm199604043341416)
        - > The loss of merely one hour of sleep can increase the risk of traffic accidents. It is likely that the effects are due to sleep loss rather than a nonspecific disruption in circadian rhythm, since gaining an additional hour of sleep at the fall time shift seems to decrease the risk of accidents.
        - > 訳: たった1時間の睡眠不足が交通事故のリスクを増やしうる。これは体内時計の小さな乱れというよりは、睡眠不足によるものだろう。フォールタイムへの移行（サマータイムの終了）が、交通事故のリスクを減らすらしいからである。

<!--

Title                                  | URL
---------------------------------------|-----------
https://scholar.google.co.jp/scholar?hl=ja&as_sdt=0%2C5&q=daylight+saving+time+energy+&oq=day
daylight saving time - Google Scholar | https://scholar.google.co.jp/scholar?start=0&q=daylight+saving+time+&hl=ja&lr=lang_en%7Clang_ja&num=20&as_sdt=0,5
daylight savings time bug - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time+bug&rlz=1C1GCEA_enJP787JP787&ei=2wxpW-PwKsry8QXn3auQCA&start=10&sa=N&biw=1240&bih=802
daylight savings time - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time&rlz=1C1GCEA_enJP787JP787&source=lnms&tbm=nws&sa=X&ved=0ahUKEwiG_4jd_NncAhVIu7wKHcbQAH0Q_AUICigB&biw=1240&bih=1294&dpr=1.5
日本に『サマータイム制』はいらない！ ( 夏 ) - 気象・歳時・防災 コラム - Yahoo!ブログ | https://blogs.yahoo.co.jp/otenki_bosai/47260331.html
Why would daylight-saving time mess up my computer? - HowStuffWorks | https://computer.howstuffworks.com/dst-bug.htm

Remember The Milk - Forums / Help / Daylight Savings Time Bug in Android | https://www.rememberthemilk.com/forums/help/12344/
March 11 calendar bug - Outlook Mac | https://social.technet.microsoft.com/Forums/office/en-US/a43a6c67-7d02-4a62-95e5-5ff931f8f7ac/march-11-calendar-bug-outlook-mac?forum=outlook

daylight savings time trouble - Google 検索 | https://www.google.co.jp/search?q=daylight+savings+time+trouble&rlz=1C1GCEA_enJP787JP787&oq=daylight+savings+time+trouble&aqs=chrome..69i57j0.12334j0j7&sourceid=chrome&ie=UTF-8
Is daylight saving time worth the trouble? Research says no | http://theconversation.com/is-daylight-saving-time-worth-the-trouble-research-says-no-86739
Why daylight saving time can be bad for your health - CNN | https://edition.cnn.com/2016/03/11/health/daylight-saving-time-health-effects/index.html
404 Blog Not Found:夏時間を支持するのは頭が春な人だけ | http://blog.livedoor.jp/dankogai/archives/51239059.html

https://www.ncbi.nlm.nih.gov/pubmed/11152980
-->
