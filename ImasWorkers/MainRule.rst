##############################
IM@S x Workerplacement (alpha)
##############################

1. 概要
==============================

Imas x Workerplacementのルール草案

最もファンからの人気を集めるユニットとして
勝ち抜くこと目的。


2. コンポーネント一覧
================================

現在編集中

* アイドルカード (1人2枚)
  
  * アクションマーカー + アイドルシール

* 成長ボード (1人1枚)
  
  * レッスンチップ (Vo, Da, Viをたくさん)
  * 思い出チップ
  * マニーチップ
  * 経験値カウンターコマ

* ゲームボード (12枚程度)
* ゲームステータスボード (1枚)
  
  * Pコマ(得点マーカー) (人数分)
  * ラウンドマーカー (1つ)

* イベントボード (1枚)
  
  * イベントマーカー (人数分)
  * イベントカード (数枚)

* アピールカード (20枚程度)


3. ゲームの準備
================================

3.1. プレイボードの準備
-----------------------

* 初期ボード(1)とラストボード(3)を抜き取ります。
* その後、残りのゲームボードから7枚を選び、
  ランダムにシャッフルをして山を作ります(2)。
* (3)の上に(2)を置いて、新たな山を作ります(4)
* 場に (1) と (4) を並べておきます。
  この時、(1)はプレイ中のラウンド、
  (4)はゲームでプレイされる残りのラウンドを表します。

* イベントカードから、初期イベント(Rookies)を取り出し、
  イベントボードの指定位置に置きます。
* 残りのイベントカードは裏向きにして良くシャッフルし、
  イベント山札を作ります。
* アピールカードは全てを裏向きにして良くシャッフルし、
  アピールカード山札を作ります。
* チップは各プレイヤーが取り易い位置に置いてください。


3.2. プレイヤーの準備
---------------------

各プレイヤーは個人ボードと対応するPマークを受け取ります。
Pマークはステータスボードの勝利点トラック0点の位置に置いてください。
また、イベントマーカーをイベントボードのポイントトラック0点の位置に置いてください。

ここで最初のラウンドのスタートプレイヤーを決定します。
Project IM@S に関する創作時間が最も長いプレイヤーが最初のラウンドのスタートプレイヤーです。
(毎回同じになってつまらないという場合には、自由な方法で決定してください)

その後、あなたが担当するアイドルを2人選んでください。
選び方については決まったルールはありませんが、
カタン取り(要説明)を推奨します。

あなたの担当するアイドルが決定したら、
そのアイドルのカード、およびアイドルコマを受け取ります。

受け取ったアイドルコマは最初のラウンドのスタートマスに置きます。
また、自分の個人ボードのVo, Da, ViアビリティのLVにコマを置きます。
初期のレベルは、アイドルカードに書かれているアビリティの合計値です。

(例: アビリティVo/Da/Vi = 2/0/1とアビリティ1/1/1のアイドルを選んだ場合、
自分の個人ボードに配置する初期レベルはVo/Da/Vi=3/1/2となる)

その後にスタートプレイヤーから時計回りに、
アイドルカードに記述されている"タイミング:ゲーム開始時"の効果を解決します。
もしも、そのカードに書かれている効果が適用順序によって異なる結果になる場合、
自分の好きな順番で効果を解決して下さい。
また、効果の解決単位はカード毎です。
複数の効果が記載されているカードで、
能力別に適応順序を配分することはできません。


4. ゲームの流れ
=================================

4.1. 概要
---------

このゲームは全部で9つのラウンドで構成されています。
そして、ゲーム全体では4回のイベントが行われる事になっており、
1, 3, 6, 9ラウンド目の終了時にイベントの結果発表が行われます。

プロデューサーとアイドルは、その道中でアイドルとしての経験を積み、
魅力を鍛え、そして思い出を築いていく必要があります。
もちろん、アイドルとして成功するために、
それと同時に、イベントで上位を狙ってファンを増やしていく必要があります。


4.2. ラウンドとアクション
-------------------------

各ラウンドのボードには以下に示すようにいくつかのスペースが存在します。
そして、このスペースには、スタートスペースとゴールスペース、およびアクションスペースがあります。
ラウンドボードには以下のような特徴があります。

* スタートスペースは1つのラウンドボードに必ず1つだけ存在する
* ゴールスペースは1つのラウンドボードに必ず1つだけ存在する
* 任意のスペースの間には矢印（パス）が引かれている
* スタートスペースからパスをたどっていくと必ずゴールスペースにたどり着ける。
* あるスペースから、同じスペースに戻ってくることはできない(ループが存在しない)。


ラウンドボードは以下のようになっています。

.. image:: images/board-sample.png


4.3. アクションの実施方法
-------------------------

ラウンドが開始されると、一番最初にスタートプレイヤーの手番になります。

手番プレイヤーは、アクションを1回だけ実行します。
アクションとは、次のような行動の事です。

* アクション: アイドルを1人選び、アイドルが今居るスペースから
  パスを1つ以上(好きな数だけ)経由することでたどり着けるスペースを1つ選び、
  アイドルをそのスペースに置く。
  その後、そのスペースに記載のある効果を解決します。

手番でアクションを行う場合、以下の行為を伴うアクションを行うことはできません。

* 1つ前のラウンドで動かしたアイドルを動かしてアクションを行うこと。
  (これを補足するため、アイドルコマの表と裏で「A」「B」の異なる文字が印字されています。
  手番の最初に動かすアイドルはA面を、２番目に動かすアイドルはB面を表に向けて
  ラウンドを実施して下さい。
  各ラウンドの開始時に限り、どちらのアイドルから動かすかを選ぶことができますので、
  そのタイミングでどちらをA、どちらをBとするかを決定してください。)

* 既に他のアイドルがいるゴール以外のスペースを選び、アクションを実施すること。
* 既に一方のアイドルがゴールスペースに居る場合、
  ゴールスペース以外のアクションを選び、アクションを実施すること。

手番プレイヤーがアクションを実施した場合、
次の順のプレイヤー(時計回りの席順)に手番が移ります。
全てのアイドルがゴールスペースに置かれた時点でラウンド終了となります。

なお、手番になっても自分のアイドルが全てゴールスペースに置かれている場合、
アクションを実施することはできません。
その代わりに、マニーチップを1枚得ます。

注意: アイドルのどちらか一方のみがゴールスペースにある場合、
残りのアイドルをゴールスペースに配置するというアクションを行う必要があるため、
その時点ではマニーチップを得る事はできません。

また、何らかのカードの効果で今の手番で動かすべきA/Bのアイドルが既にゴールしており、
もう一方のアイドルがゴールに置かれていない場合に限り、
A/Bの制約なくゴールしていないアイドルを選択して
ゴールスペースに配置するアクションを行うことができます。


4.4. アクションの種類
---------------------

ゲーム中のアクションでは、マスに明記されている以下の内容を実行します。

- レッスン: アクションに記載されている数だけのチップ(Vo, Da, Vi)を得る
- 特訓: アクションに記載されているチップ(Vo, Da, Vi)を消費して、
  個人ボードのアビリティを上昇させる
- ある日の日常: アクションに記載されている数だけの思い出チップを取得する
- 営業: アクションに記載されている数だけのアピールカードを取得する
- イベント: 現在開催されているイベントに参加し、
  イベントの条件をクリアすることでイベントポイントを上昇させる
- ゴール: 特に何も起こりません。


4.5. ラウンド終了処理
---------------------

全てのプレイヤーの全てのアイドルがゴールスペースにたどり着くと、
その時点でラウンドは終了となります。

ラウンドが終了した後、以下の処理を行います。

- 全てのアイドルコマを現在のラウンドボードから取り除く
- ラウンドボードを横に寄せ、最初に作成したラウンドボードの山の
  一番上からラウンドボードを今までプレイしていた場所に置きます。
  その後、そのラウンドボードのスタートスペースにすべてのアイドルコマを置きます。


次のラウンドのスタートプレイヤーは、前のラウンドで最も最初にゴールしたプレイヤーになります。
ゴールしたとは、２人のアイドルコマを両方ともゴールスペースに置くことを意味します。


4.6. プレイヤーリソース
-----------------------

このゲームでは各プレイヤーは以下のリソースを得ます。
それぞれ、次のような効果を持っています。

(なお、イベントについては次の章でくわしく説明します)

- アビリティチップ(Vo, Da, Vi)
  
  - 特訓でアビリティを上昇するために使用できます。
  - イベントで一時的なアビリティのブーストを得ることができます。

- 思い出チップ
  
  - 自分の番であればいつでも使用することができます。
    この場合、好きなアビリティチップを3個得ることができます。
  - イベントを「成功」で終えた時に使用できます。
    この場合、そのイベントで得られるイベントポイントを2倍にします。
    この用途で利用する場合、思い出チップは1枚しか使用できません。

- マネーチップ
  
  - 自分の番であればいつでも使用することができます。
    この場合、好きなアビリティチップを2個得ることができます。
  - アイドルをアクションマスに置いた直後に使用することができます。
    この場合、そのアクションマスの内容に関わらず「イベント」アクションを実行できます。

- イベントカード
  
  - カードごとに様々な効果があります。
    利用タイミングとその効果はカードによって異なります。
  - イベントカードを取得した場合、裏向きにして自分のボード上において置きます。
    イベントカードの所持上限は３枚です。
    イベントカードには、場に残って効果を発揮し続けるものと使い捨てのものがありますが、
    場に残っているものも所持枚数に数えます。
    所持上限を超えてイベントカードを取得した場合、好きなカードを捨ててください。
    表向きのカードを捨てた場合、その効果は発揮されなくなります。


タイミングを守っている限り、利用できるリソースの数に上限はありません。
また、チップを使用した場合、そのチップは全て場に返し、手元から無くなります。


5. イベント
===========

5.1. イベントの内容
-------------------

プレイヤーはアクションを実行した場合、
以下のいずれかの条件を満たすことでイベントに参加することができます。
イベントに参加できる回数に上限はありません。

- "イベント"アクションスペースにアイドルを置き、アクションを行う
- スタート、ゴール以外のアクションスペースにアイドルを置き、マニーチップを1枚使用する。
  この場合、本来のアクションの効果を解決せずにイベントに参加できる。
- 特定のアピールカードやアイドル個別のカードの効果を解決した場合


プレイヤーはイベントに参加した場合、以下の手番を順に実行します。

- 現在開催されているイベントカードに記載されているレベルを1つ選択する
- レベルごとに「Vo, Da, Viの目標値」が設定されている。
  目標値はプレイしているラウンドや、イベントごとに変動するので、
  レベルを選んだ後にイベントの目標値を確定させる。
- イベントに参加したプレイヤーの個人ボード上にある全てのアビリティが
  目標値「以上」になると、今回選択したイベントは「成功」となり、
  目標値未満だと「失敗」となる。
- プレイヤーは「成功」「失敗」を判定する前に、好きな数だけのVo/Da/Viチップを使用できる。
  今回参加したイベントに限り、ここで消費したチップの種類のアビリティが一時的に上昇する。
- イベントを成功させると、イベントカードのレベルに記載されているイベントポイント(EVP)を得る。
- イベントが失敗で終わった場合、何も得られない。


5.2. イベント結果発表
---------------------

1, 3, 6, 9ラウンド目の終了時にイベントの結果発表が行われます。
これらのラウンドが終了した場合、以下の処理を順に解決してください。

- イベント終了時のEVPと同数だけ、各プレイヤーのポイントマーカーを進めます。
- EVPの高い順序でプレイヤーに順位づけをします
  同点の場合は同順位として扱います。
- 順位の高い方から順にイベントに書かれている順位報酬を与えます。
  同着の場合、合算の後折半します(端数切捨て)。
- 最後にイベントマーカーを０の位置に戻します。

例: 4人ゲームで、1位=10点、2位=5点、3位=2点 のイベントが開催され、
結果発表時にAさんは3EVP, BさんとCさんは2EVP, Dさんは1EVPを獲得していました。
この時、1位はAさん、2位はBさんとCさん、4位はDさんとなります。
同様に、得点配分はAさんに10点、BさんとCさんに3点ずつとなります。
(Dさんは全体で4位なのでイベント報酬を得ることはできませんでした)


6. 最終ラウンド処理
===================

9ラウンド目、すなわち最終ラウンドだけ、以下の処理を行います。

- 最終ラウンドでは、ゴールした順序を記録します。
  最終ラウンドのゴールには1～5までの数値が記載してあるので、
  ゴールした順に1からアイドルコマを2つ重ねて、それらのスペースに配置してください。
- 全員がゴールした後、イベント結果発表を行います。
- イベント結果発表の終了後、「後からゴールしたプレイヤーから順番」に「特訓」のアクションを行います。
  このアクションを行う前に、自身の手元にあるリソースを可能な限り使用できます。
  (なお、この時点で既にイベントは終了しているのでマネーチップをイベントに使う事はできません)
- 全プレイヤーが成長を終えた後、各アイドルのVo, Da, Viアビリティを比較します。
  これらの数値が高い順に順位を付け、プレイ人数に応じた得点を得ます。
  同点の場合は合算の後折半（端数切捨て）です。
- 以上の処理が終了した後、ポイントを比較します。
  最も高いポイントを得たプレイヤーとアイドルが
  ゲームの勝利者として最高の名誉を受け取ることになります！
  （同点の場合はその全てのプレイヤーが勝利者です！）


Appendix
========

※現在考案中


A1. アイドル一覧
----------------

.. list-table::
  :header-rows: 1

  * - 項目
    - 内容
  * - 名称
    - 天海 春香
  * - 初期アビリティ
    - Vo2, Da1, Vi1, 思い出1
  * - 固有アビリティ
    - あなたは「ある日の日常」において思い出を取得する場合、
      思い出チップを1つ追加で獲得する。


.. list-table::
  :header-rows: 1

  * - 項目
    - 内容
  * - 名称
    - 如月 千早
  * - 初期アビリティ
    - Vo3, Da1, Vi1, 思い出0
  * - 固有アビリティ
    - あなたはレッスンDa/Viのアクションを実行するときに、
      Da/Viのチップの代わりにVoのチップを得ても良い。


.. list-table::
  :header-rows: 1

  * - 項目
    - 内容
  * - 名称
    - 星井 美希
  * - 初期アビリティ
    - Vo1, Da1, Vi3, 思い出0
  * - 固有アビリティ
    - あなたは自分の手番を始める前に
     「特訓: Ability / 2 Chips」のアクションを行うことができる。


A2. イベント一覧
----------------

目標値の記載方法は以下の2通りです。

* VoX, DaY, ViZ方式: それぞれのアビリティに必要な数値が固定されている場合の記載
* (X, Y, Z)方式: アビリティの種類は問わないので、
  X, Y, Zに自由にVo/Da/Viを割り当てて、
  目標の数値を超える場合の記載

* 例1: Vo2, Da2, Vi2: Vo, Da, Vi全てのアビリティが2以上であればそのレベルのイベントに成功できる。
* 例2: Vo5: Voのアビリティが5以上であればそのレベルのイベントに成功できる(Da, Viのアビリティは何でもよい)
* 例3: (4, 2, 2): Vo, Da, Viの内、1つのアビリティが4以上、残り2つのアビリティが2以上でイベントに成功できる。
  例えば、Vo=4, Da=2, Vi=2でも良いし、Vo=2, Da=2, Vi=4でも良い。

- Rookies

第1ラウンドで必ずプレイされるイベント。

* Lv1
  
  * 目標値: (2, 1, 1)
  * 成功時報酬: 1EVP

* Lv2
  
  * 目標値: (3, 2, 1)
  * 成功時報酬: 2EVP, 思い出+1

* Lv3
  
  * 目標値: (4, 3, 2)
  * 成功時報酬: 2EVP, 思い出+1, イベントカード+1

