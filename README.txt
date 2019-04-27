# Summary
1)git init . などで空のリポジトリを作成
2)git config core.sparsecheckout tureに設定
3).git/info/sparse-checkoutを編集して，cloneするディレクトリやファイルを指定する

#sparse-checkout
/html
!/html/css

# HW
・作業ディレクトリに表示されないだけで，fetchされていたり，ローカルリポジトリにファイルが存在していたら意味がない．
→50MBくらいのデータを作って，普通にfetchした場合と.gitのサイズを比較してみる

・すでにfetchしてしまった場合，あとからsparsecheckoutを追記したらどうなる？名前から想像するにcheckoutを切り替えるたびに参照されるっぽいが．