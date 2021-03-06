
BASY(babanuki no syusaku)
----

BASYは数字のヒントとなる「色」が裏からわかるカードを用いることで推理や戦略要素を加えた、ゲーマー好みに改造されたババ抜きです

プレイURL: https://fuyutsubaki.github.io/BASY/index.html

## ゲームの目的

- ババ抜きです。ラウンド終了時に持っていたカードの合計が失点になります。
なるべく失点しないようにしましょう

## カードの内訳
カードの色は4色あり、それぞれに英字カードと数字カードがあります

- 赤: {1,96,101} 各4枚 {B,S} 各1枚
- 青: {25,50,75} 各4枚 {A,B} 各1枚
- 緑: {3,5,107} 各4枚 {S,Y} 各1枚
- 橙: {0,4,8,32} 各2枚 {16} 各4枚 {A,Y} 各1枚

合計で 14x4で56枚

## ラウンドの流れ

- カードを引いた後、自分の手札に同じ数字のカードのペアがあった場合、それらのカードを捨て札にします
  - (注：英字カードは捨てれません)

- ターンプレイヤーは他のプレイヤーの手札からカードを一枚引きます。この時、☒マークがついているプレイヤーからはカードを引くことはできません
- カードを引かれたプレイヤーは☒マークが付き、次のターンプレイヤーになります
- すべてのプレイヤーに☒マークが付いた時、すべてのプレイヤーの☒マークを外します

## ラウンドの終了条件
以下のいずれかを満たしたとき,ラウンドを終了する

- 終了条件1. いずれかのプレイヤーの手札が0枚になった場合
- 終了条件2.「全ての数字カードが捨てられている色」がX色以上になる(Xはゲーム開始時は3)
- 終了条件3. いずれかのプレイヤーが英字カード4種(BASY)がそろった場合
    (注：強制効果である。「カードがそろったことを宣言してラウンドを終了させることができる」ではない。)

## ラウンドの終了処理
- 手札の数字カードの合計を失点します(英字カードは無視する)
- このラウンドが「終了条件3」で終了してた場合、
次のラウンド以降、「終了条件2」の 「～がX色以上になる」のXの値を1減らします

# ゲームの終了条件
- いずれかのプレイヤーが500点失点する
- ラウンドが「終了条件3」で3回終了した場合

## ヒント
- 捨て札とプレイヤーの手札の色は公開情報です。よく考えましょう
- カードの数字は色によって不均質です。よく考えましょう
- BASYが発生するとゲームの終了が早くなり、大きな数字が捌ききれない可能性が増えます。よく考えましょう
- BASYは理不尽にやってきます。あきらめましょう
