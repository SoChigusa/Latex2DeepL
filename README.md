# Latex2DeepL

## ToDo list

* \def\new\old 型の newcommand に対応
* document環境が第1階層にないと対応できない点を改善 [1905.04319]
* 上と関連して、document環境内に文章全体を覆う環境が別にあると壊滅的な点を改善 [2011.02484]
* 上と関連して、section/footnote環境やfigure環境のcaptionなども翻訳
* 段落の途中にコメント行がある場合、翻訳後にコメントの後に改行を追加しないと段落の残りの文章が全てコメントアウトされてしまう
* newcommand の行の後ろにコメントライン（{}含む）があるときの取り扱い[1004.1403]
* align/equation等の環境内にある , や . の追加
* （arxivからのダウンロード）・日本語化のための処理・bblのinputを自動化
* DeepLが作り出した存在しないタグの処理 [2102.06179]
* 上と関連して、DeepLが作り出した桁の少ないタグの処理 [0810.2998]
* \margin 2.7 in などの設定を翻訳しない [0810.2998]
* bblを読み込んでreferenceを追加するためのサポート？
* 分割タイプセットに対応する？ [2103.14043]
* 文章中の \textit{} 等の処理？ [2104.10280]
* 複雑な \def\ket#1{...} などの対応 [0810.2998]
* inputファイル名に複数のピリオドを含む時の対応？
