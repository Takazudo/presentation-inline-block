# inline-block

[@Takazudo](https://twitter.com/Takazudo)

----

`display: inline-block` な要素の中に  
`display: block` な要素入れたらどうなんの？  
そもそもそれアリなの？

## アリ

----

## boxの種類

* block box
* inline box
* list-item
* table類

----

## inline box と atomic inline box

inline box の一種に atomic inline box ってのがある

* [demo](http://codepen.io/takazudo/pen/lJoaB?editors=110)

---

### inline box

* line box の中に並べられる
* 行の中に入らんかったら次の行にまたがる

---

### atomic inline box

* inline box と 同じように line box の中に並べられる
* だけど外側からは影響されない box<br>（置き換え要素みたいな感じで計算される）
* そんで中身は block box

要するに `inline-block` だけど。

----

## こんな感じ

* [demo](http://codepen.io/takazudo/pen/HeKsl?editors=110)
* [demo](http://codepen.io/takazudo/pen/emIvc?editors=110)
* [demo](http://codepen.io/takazudo/pen/sJguz?editors=110)

----

## 応用例

* [demo](http://codepen.io/takazudo/pen/lzFbL?editors=110)
* [demo](http://codepen.io/takazudo/pen/wuoxl?editors=110)

----

## まとめ

* 応用聞くのでちゃんと理解してるとお得
* 大体`display:table`系の方が便利なこと多いけど

----

## 参考

* [Visual formatting model details](http://www.w3.org/TR/CSS2/visudet.html)
* [Visual formatting model - Web developer guide | MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Visual_formatting_model)
* [書籍などに紹介されていない display : inline-block について](http://www.yomotsu.net/works/081016cssnite/)

