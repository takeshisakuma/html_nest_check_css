# HTMLネストチェックCSS

入れ子にできないHTMLタグを入れ子にしている場合に視覚的に確認できます。

※警告色はSCSSの変数で一括変更できます。

使用方法：style.cssファイルを作成中のHTMLから読み込んでください。


## 対応状況　

現時点で非対応の親タグ 
math svg noscript canvas button a del ins video audio map

## タグ直下のテキスト

CSSではテキストノードを選択できないので、タグ直下にテキストを置く違反を判定できない

資料：テキストを直下に置けるタグ

title style body article section nav aside h1 h2 h3 h4 h5 h6 header footer address p pre blockquote li dt dd figure figcaption div main a em strong small s cite q dfn abbr data time code var samp kbd sub sup i b u mark ruby rb rt rtc rp span ins del iframe object video audio map caption th td form label button datalist option textarea output progress meter fieldset legend details summary dialog script noscript template canvas
