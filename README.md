# 問題
花子さんがスーパーで下記の商品を買いました。  
合計金額（消費税8%含む）をブラウザに表示しましょう。  
ただし、小数点が出る場合は無視してもOKとします。

|豚肉|にんじん|じゃがいも|お米|
|:--:|:--:|:--:|:--:|
|380円|90円|120円|2000円|

# ヒント
連想配列、for in文、算術演算（`+`と`*`）を使います。  
合計金額を変数に入れて足し算や掛け算のような演算をする場合、一度Number型に定義する必要があります。  
```js
// 例えば下記のような指定をします。
var total = 0;
```
#### 文章にしてみる
行いたい処理を文章化することで事象の整理ができます。  
この問題であればこのような読解ができます。
```
basketという変数に、豚肉を380、にんじんを90、じゃがいもを120、お米を2000という連想配列を入れる。
合計金額を格納する変数totalを定義する。
for inで連想配列の金額を1つずつtotalに足していく。
totalに消費税の1.08を掛け算してdocument.writeでtotalを表示する。
```

# 解答例
[解答例はこちら](http://codepen.io/anon/pen/MwYYxL)
