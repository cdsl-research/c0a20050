# status cord search
# 概要
ECログを検索するコマンドをshell scriptに保存しました．
# 検索の内容
今回のソースコードは以下に示しているサイトのECログの検索を行ったものです．

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/Z834IK

検索の条件はHTTPのステータスコードの400番台と500番台です．

検索ファイルの形式はcsvファイルでgrepコマンドを使っています．

今回の検索は検索の時間も測っており，そのコマンドは

`/usr/bin/time`

になります．
