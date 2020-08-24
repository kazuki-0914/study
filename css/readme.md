# css
Tips
<<CSSの指定方法>>
外部ファイル
    <link href="ファイルパス" rel="stylesheet" type="text/css">

<<指定方法>>
id
class
子要素を指定 セレクタをスペースでつなげる
直下の子要素の指定 >でつなげる
隣接している要素の指定 +
議事クラス
:first-child 最初
:last-child 最後
:ntn-child(n) n番目
:ntn-child(odd) 奇数番目
:ntn-child(even) 偶数番目

<<セレクタ>>
color テキストの色
font-size テキストのサイズ
font-weight テキストを太字にする
text-decoration テキストの装飾
text-align テキストの配置

display
inline インライン要素に指定します
block ブロックレベル要素に指定します
inline-block インライン要素でありブロック要素の指定ができる
none 要素ごとないものとして扱われる

line-style-type
<ul>
circle 中空円
square 四角形(塗りつぶし)

<ol>
lower-roman 小文字のローマ数字
lower-greek 小文字のギリシャ語

none マーカーを非表示

line-style-position
line-style-image
linestyle でまとめて書ける

<<参考情報>>
ブロックレベル要素、インライン要素を意識する必要ある
ボックスモデル

<<拡張機能>>
CSSTree validator
HTML CSS Support

<<参考URL>>
CSSリファレンス https://developer.mozilla.org/ja/docs/Web/CSS