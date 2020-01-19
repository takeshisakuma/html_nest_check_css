# HTMLネストチェックCSS

入れ子にできないHTMLタグを入れ子にしている場合に視覚的に確認できます。

※警告色はSCSSの変数で一括変更できます。

使用方法：style.cssファイルを作成中のHTMLから読み込んでください。


## 対応状況　

対応済親タグ　body

未対応親タグ　article section nav aside h1 h2 h3 h4 h5 h6 header footer address p hr pre blockquote ol ul li dl dt dd figure figcaption div main a em strong small s cite q dfn abbr data time code var samp kbd sub sup i b u mark ruby rb rt rtc rp bdi bdo span br wbr ins del picture img iframe embed object param video audio source track map area math svg table caption colgroup col tbody thead tfoot tr th td form label input button select datalist optgroup option textarea keygen output progress meter fieldset legend details summary dialog script noscript template canvas

## 既知の問題

CSSではテキストノードを選択できないので、タグ直下にテキストを置く違反を判定できない
