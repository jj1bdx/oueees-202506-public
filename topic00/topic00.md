theme: Plain Jane, 2
footer: Kenji Rikitake / oueees 20240618 topic00
slidenumbers: true
autoscale: true

# oueees-202406 topic 00:
# [fit] 電気工学特別講義
# [fit] 2024年6月18日分
# [fit] イントロダクション

<!-- Use Deckset 2.0, 16:9 aspect ratio -->

^ 大阪大学基礎工学部 電気工学特別講義 2024年6月18日分 イントロダクションです

---

# [fit] OU EE ES Lecture Series
# [fit] June 18, 2024
# [fit] Lecture introduction

---

# Kenji Rikitake

## りきたけ けんじ

## 力武 健次

18-JUN-2024
School of Engineering Science, Osaka University
On the internet
@jj1bdx

Copyright ©2018-2024 Kenji Rikitake.
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

![right, fit](jj1bdx-smiling-photo-20210416.jpg)

^ 講師の力武 健次といいます。よろしくお願いします。

---

# CAUTION

Osaka University School of Engineering Science prohibits copying/redistribution of the lecture series video/audio files used in this lecture series.

大阪大学基礎工学部からの要請により、本講義で使用するビデオ/音声ファイルの複製や再配布は禁止されています。

^ 大阪大学基礎工学部からの要請により、本講義で使用するビデオ/音声ファイルの複製や再配布は禁止されています。ご注意ください。

---

# Lecture notes and reporting

* <https://github.com/jj1bdx/oueees-202406-public/>
* Check out the README.md file and the issues!
* Keyword at the end of the talk
* URL for submitting the report at the end of the talk

^ レクチャーノートはGitHubのこのURLに掲載しています。

---

# [fit] 2024:
# [fit] unstable and volatile world

^ 2024年は流動激動の年になっています。

---

## It's already June 2024, but
# [fit] *COVID-19 is still there*
## [fit] My family recently suffers from COVID-19
## [fit] It persists for months

^ この講義をしているのは2024年6月です。世間ではコロナあるいはCOVID-19はなくなったと言われていますが、実際にはCOVID-19の日次感染者数は一定数以上を保っており、なくなったとはとても言えない状態です。私もコロナに2022年7月に罹患し、1ヶ月ぐらい咳が残りました。それ以来少し集中力を欠いている状態が続いています。そして最近家族がコロナにかかりました。

---

# [fit] To prevent COVID-19 outbreak again:
## [fit] Practice basic hygiene procedures
## Wash your hands
## Minimize the virus exposure
## Get vaccinated
## Wear masks whenever required

^ コロナの再流行を防ぐためには、基本的な公衆衛生の手順を守ることが必要です。手洗いを欠かさず、ウイルスにさらされるような活動を最小限にして、ワクチンを打ち、必要な場所ではマスクを使い続けることが必要です。感染症法上の指定が緩くなったとしても、各自で続けていく必要があります。

---

# [fit] Wars
## [fit] or "regional conflicts"

^ 2022年のロシアによるウクライナ侵攻以来、イスラエルによるガザ侵攻など、地域紛争と呼ばれる戦争が日常化しています。

---

# [fit] *Japan has already engaged in the war*

^ 忘れてはならないことは、日本はこれらの地域紛争にすでに関わりと立場を持って活動しているということです。

---

# As of June 2024, Japan has most deeply committed in the military and peace-keeping activities on regional conflicts since 1952

^ 2024年6月現在、1952年にサンフランシスコ平和条約が締結されて以来、日本がこれだけ地域紛争や平和維持活動に深くかかわったことはないものと思います。

---

# The levels of tension in the regional conflicts which Japan is engaged in are rising to much higher levels than those in the cold war during 1945-1991

^ 私は1965年生まれで、学生時代は1980年代半ばから後半の冷戦まっただ中でした。当時も欧州では戦術核兵器が使われる可能性が取り沙汰されていました。しかし、現時点で日本がかかわっている地域紛争の緊張レベルというのは、1945年から1991年まで続いた冷戦時代よりもはるかに高く厳しいものだと思っています。

---

# We are under the process of revising our understating of how the world is built and formed

^ 現在我々は世界がどのように作られて形成されてきたかの認識を根本的に変える過程にあるのだと思います。

---

# [Fit] The Digital Divide has become irrelevant
# [fit] The Physical Divide

^ 認識という意味では、21世紀になってからずっとデジタルディバイドというコンピュータなどへの習熟度の違いによる人々の分断が取り沙汰されていますが、最近は物理的な資源へのアクセスがどれくらい簡単なのかによる違い、つまりフィジカルディバイドという問題が注目されています。

---

# The Physical Divide [^1]

>Digital is now cheap, it's physical that is expensive.
70 years ago the cost of putting a bunch of transistors on a chip was astronomical. Now that’s cheap. What’s expensive is putting a bunch of people in a room.
-- Balaji S. Srinivasan


[^1]: <https://twitter.com/balajis/status/1247518697385684992?lang=en>

^ これは2020年4月のTweetからの引用です。デジタルの値段は安くなったけど、フィジカルは高価なものになったという話です。70年前、つまり1950年代にはトランジスタを集積するのには莫大なコストがかかったけど、今はとても安くなっていて、むしろたくさんの人達を同じ部屋に入れるコストの方がずっと高くなってしまった、という話ですね。これはCOVID-19による価値観の変化もありますが、実際問題として人を運ぶためのコストは無視できなくなっています。航空機の燃料消費は地球温暖化の元凶として批判の対象になっています。

---

# [Fit] Recognition of the Western nations including Japan:
# [fit] Digital-first society has come
# [fit] Internet is infrastructure
# [fit] Software builds the world

^ そういう意味では、日本を含む西側の国々の社会の認識としては、もうデジタルファーストな社会が来ていて、インターネットはすでにその基盤となっていて、世界を作るのはソフトウェアであるという考え方が浸透しつつあります。

---

# In reality:
# [fit] Physical ubiquity matters
# [fit] i.e., we need ample supplies of daily necessities
# [fit] to keep the software world running smoothly!

^ しかし、2022年以降の世界中の物資受給の混乱からもわかるように、ソフトウェアの世界をなめらかに回していくには、日々の物資が潤沢にあることが必要なのです。つまりphysical ubiquity、日本語でいえばフィジカルなものがいたるところにあること、という前提が大事になってきます。

---

![original,fit](matt-palmer-kbTp7dBzHyY-unsplash.jpg)

# [fit] Infrastructure crises

## [fit]
## [fit] Broken supply chains: food, semiconductors
## [fit] Limited natural resources: crude oil, natural gas
## [fit] Global warming and water/electricity shortages
## [fit]
## [fit] *Are we heading into the apocalypse?*

^ そして現在、いろいろなところでインフラストラクチャー、あるいは社会基盤の危機が続いています。サプライチェーンが壊れたことにより、食料危機や半導体不足が起こっています。また原油や天然ガスの供給不足、そしてそのことを戦争遂行に利用する勢力によって、エネルギー価格の高騰が発生しています。地球温暖化による水不足や電気不足も起こっています。この10年ぐらいずっと語られつづけているのは、世界の終わりに向かって人類が突き進んでいるのではないか、ということです。普段生活しているとそんな感じは全然しないんですが、その認識自体が問題なのかもしれません。

---

# Cruelty and inequality going on everywhere by people with power to enslave oppressed and marginalized people

^ そして世界中の権力者によって、弾圧されたり辺境に追いやられている人達が、奴隷のように扱われて残酷かつ不平等な扱いを受けているわけです。

---

<!-- one or two pics here -->

---

# [fit] We live in the global warzone

^ もはや地球のどこにいても戦争とは無縁でいられない状況になったわけで、我々はそんな世界を生き抜いていかなければならないわけです。

---

# [fit] Safety first
# [fit] Stay alive
# [fit] Get out of slavery
# [fit] Prevent slavery

^ 安全を守ること、生き続けること、奴隷的立場から脱出すること、そして人を奴隷にすることを防がないといけないわけです。

---

# [fit] Who I am
# [fit] 自己紹介

^ 前置きが長くなりましたが自己紹介です。

---

# [fit] Software Engineer
# [fit] Professional Internet Engineer

^ かつてはプロフェッショナル・インターネット・エンジニアと名乗っていました。今はソフトウェアエンジニアと簡単に名乗ることが増えました。

---

# [fit] 技術士（情報工学部門）
# [fit] 力武健次技術士事務所 所長
# 情報処理安全確保支援士

^ 今は技術士の仕事をしています。技術士というと建設業で良く知られていますが、私は情報工学部門、つまりコンピュータ関連での調査研究をしています。自分の名前を付けた技術士事務所の名前を個人事業主の屋号にしています。また、情報セキュリティの資格である情報処理安全確保支援士の仕事もしています。

---

![right, fit](pepaken_logo.jpg)

# [fit] Guest Researcher
# [fit] Pepabo R&D Institute
# [fit] GMO Pepabo, Inc.
# [fit] GMOペパボ株式会社
# [fit] ペパボ研究所 客員研究員

^ 主な研究の仕事の一つは、GMOペパボ株式会社のペパボ研究所の客員研究員、そして同社の技術顧問として日々の業務からインターネットそして世界をどうやって研究開発の視点からもっとおもしろくしていくかに取り組んでいます。

---

# My career

Erlang, Elixir, C, FreeBSD, Linux, TCP/IP, PHP, mruby, Lua, C++, C#, Visual Studio, Moodle, macOS, Windows, Vim, VS Code, Arduino, AVR, radio engineering, music, distributed systems, fault tolerance, software defined radio, Python, R, signal processing, adaptive filter, machine learning and deep learning apprentice, whatever.

34 years in Computer Science, 19 years since PhD, 48 years of ham radio op as @jj1bdx, 2010-2012: Professor, ACCMS/IIMC, Kyoto University, ACM Senior Member, whatever.

^ 自分の職業としてはいろいろなことをやってきました。1990年に最初に社会人として就職してからもう34年になります。阪大の情報科学研究科で博士号を頂いてから19年が経過しました。京大の教授をやっていたこともあります。

---

# My recent career:

## [fit] I've got laid off on June 2013
## [fit] 10 years of ongoing survival
## [fit] as an independent IT consultant
## [fit] and a *software engineer*

^ とはいえ、10年前の2013年6月には、当時の勤務先から戦力外通告を受けました。会社都合退職といえば聞こえがいいですが、要するにクビになったわけです。その後は日々試行錯誤しながら、ITコンサルタントとソフトウェアエンジニアとして、必死に生きてきました。今年2024年の4月で、個人事業開業10周年になります。

---

# [fit] Past records are meaningless
# [fit] You need to live your life and earn money
# [fit] ... then you can work on what you really want to do

^ この10年ずっと肝に銘じていることは、過去の業績というのは何の役にも立たないこと、そして人生にとって一番大事なのはまず自分の人生を生きてしっかりカネを稼ぐこと。それをやって初めて自分の好きなことをやることができる、ということですね。

---

# [fit] Ignore past achievements
# [fit] Focus on *now*

^ 過去の業績に囚われずに、今に集中する。それしかありません。

---

# [fit] Ignore everybody
# [fit] to stay creative and maintain originality

^ あとは、自分の創造性と独自性を保ち続けるためには、他人は全員無視する、ということでしょうか。ソーシャルメディアの世の中になった現代では、他人の意見が怒涛のごとく流れてくるので、よほど自覚して自分を守らないとすぐに流されてしまいます。流されることを防ぐためには多少迷っても世間の付き合いとかしがらみを切っていかないといけない、と日々思って実行しています。

---

# Lecture theme:
# [fit] Information delivery on internet

^ この講義のテーマは、「インターネットの情報伝送」です。

---

# In other words:
# [fit] How internet works

^ 言い換えれば、どうやってインターネットが動いているか、の基本に触れるべく話をしていきます。

---

# [fit] 容錯設計
# [fit] Fault-tolerant design

^ 第二次大戦後に、フォールトトレラント、平たくいえば何か障害や事故が起こってもシステムを止めずに動かし続ける技術というのが追求されてきました。これを表現する4文字の中国語を日本語で読むと、「ようさくせっけい」、つまり錯誤を容認する設計、と書くそうです。今のインターネットは、このフォールトトレラントな設計のひとつの実装を実現したもの、ということがいえます。

---

# [fit] Internet is a survival technology

^ このイントロダクションでずっと「生き抜く」ことについて話をしてきましたが、インターネットもまたサバイバルのための技術だということがいえると思います。

---

# [fit] Modern life is full of failures
# [fit] How internet works under failures?

^ 現代の生活はちょっとしたことで電気が止まったりコンピュータが動かなくなったりするという事故に溢れているわけです。そんな状況下でどうやってインターネットを動かし続けるかということを考えなくてはいけません。

---

# Technology 1:
# [fit] Packet switching

^ この講義では主に3つの要素技術について触れていきます。ひとつめはパケット交換についてです。

---

# Technology 2:
# [fit] Flexible packet routing

^ 2つめはパケットをどの経路で通すかを柔軟に制御する技術です。

---

# Technology 3:
# [fit] Centralization, and:
# [fit] decentralization

^ 3つめは集中と脱集中という技術の実装におけるシステムの組み方や特徴の違いについて話します。

---

# Topic sections (1/3)

* Latency and Laws of Physics
* Centralized communication
* Multiplexing
* Packet switching
* Routing basics

^ 具体的な話題として、物理の法則と遅延、集中型コミュニケーション、多重化、パケット交換、基本的な経路制御、

---

# Topic sections (2/3)

* IP addresses
* Routing in details
* Network transports
* Cloud computing basics
* Social implication of cloud computing

^ IPアドレス、経路制御の詳細、ネットワークトランスポート、クラウドコンピューティングの基本とその社会的な影響について、

---

# Topic sections (3/3)

* Network fault-tolerance
* Network services and programming trends
* Wireless/radio and internet
* Information warfare and radio surveillance
* "Artificial Intelligence" and the reality
* Reference books
* Career choice

^ そしてネットワークのフォールトトレランスあるいは耐障害性、最近のプログラミング、無線とインターネット、情報戦と無線の監視、AIとその現実、参考文献、最後に社会人としての進路選択について話していきます。

---

# Summary:

# [fit] Divide data into packets
# [fit] Route flexibly and wisely
# [fit] Decentralize and distribute

^ 話の概要としては、データをパケットに分割し、そのパケットを柔軟かつ賢く経路制御して、集中させることなく分散して配送していく、というのがインターネットの情報伝送の基本的なことですね。

---

# [fit] OK let's get down to business!

^ それでは前置きが本当に長くなってしまいましたが、本題に移ります。この後にイントロダクションのキーワードがあります。

---

# Picture credits:

* My photo: by Suzuki Shin, at 鈴木心写真館, courtesy [Wantedly Official Profile](https://www.wantedly.com/id/jj1bdx)

<!--
Local Variables:
mode: markdown
coding: utf-8
End:
-->

