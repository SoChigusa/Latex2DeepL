# Latex2DeepL

## ToDo list

* document環境が第1階層にないと対応できない点を改善
* 上と関連して、section/footnote環境やfigure環境のcaptionなども翻訳
* align/equation等の環境内にある , や . の追加
* equation 環境を \beq, \eeq などの自作コマンドで書いている場合、環境内に日本語訳が混ざってしまう
* 防ぎきれなかった翻訳ミスによる式の欠落をソースファイルに書き残しておく
* DeepLが作り出した存在しないタグの処理[2102.06179]
* bblを読み込んでreferenceを追加するためのサポート？
* 分割タイプセットに対応する？ [2103.14043]
* 文章中の \textit{} 等の処理？ [2104.10280]
