# Summary
1)git init . などで空のリポジトリを作成
2)git config core.sparsecheckout tureに設定
3).git/info/sparse-checkoutを編集して，cloneするディレクトリやファイルを指定する
#sparse-checkout
/html
!/html/css
