<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" type="text/css" href="common.css" />
    <title>HTML5</title>
  </head>
  <body>
    <hr />
    寄せたい要素の種類を確認する<br />
    1.インライン要素<br />
    文章などの一部となる要素。高さの指定などができないが、勝手に横並びになる。<br />
    2.ブロック要素<br />
    コンテンツのひとかたまりとなる要素。高さなど自由に指定できるが、横並びにならない。<br />
    3.インラインブロック要素<br />
    インライン要素のように横並びにできたり、ブロック要素のように高さが指定できたりする<br />
    <hr />

    1.左右中央に寄せる<br />

    1-1.インライン要素　→　text-align:center<br />
    <div class="centering_parent_1-1">
      <span class="centering_item_1-1">
        インライン要素です
      </span>
    </div>

    <br />

    1-2.インライン要素　→　margin: 0 auto<br />
    <div class="centering_parent_1-2">
      <div class="centering_item_1-2">
        ブロック要素です
      </div>
    </div>

    <br />

    1-3.インラインブロック要素　→　text-align:center<br />

    <hr />

    2.上下中央に寄せる<br />

    2-1.インライン要素　→　vertical-align:middle<br />
    <div class="centering_parent_2-1">
      <span class="centering_item_2-1">
        インライン要素です
      </span>
      <span class="centering_item_2-1 font_big_2-1">
        インライン要素です
      </span>
    </div>

    <br />

    2-2.ブロック要素　→　display:table-cell　&　vertical-align:middle;<br />
    <div class="centering_parent_2-2">
      <div class="centering_item_2-2">
        ブロック要素です
      </div>
    </div>

    <br />

    2-3.インラインブロック要素　→　display:table-cell　&　vertical-align:middle;<br />

    <hr />

    3.上下左右中央に寄せる<br />

    3-1.インライン要素 , ブロック要素 , インラインブロック要素<br />
    →　position: absolute;　&　top,bottom,left,right:0;　&　margin: auto;<br />

    <div class="centering_parent_3-1">
      <div class="centering_item_3-1">要素</div>
    </div>

    <br />

    →transform
    <div class="centering_parent_3-2">
      <div class="centering_item_3-2">
        上下左右中央に寄せます
      </div>
    </div>

  </body>
</html>
