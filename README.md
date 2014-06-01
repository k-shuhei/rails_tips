rails_tips
==========

rails tips

- ooでcheckout

`$ git config --global alias.co checkout`


- コミット時のエディタをvimに

`$ git config --global core.editor "vim -w"`

- 前回のコミット時の状態に戻す

`$ git checkout -f`

- fatal: remote origin already exists.がでたとき
originを再登録する

```
$ git remote rm origin
$ git remote add origin git@github.com:(githubのid)/(リポジトリ).git
$ git push -u origin master
```


- `$ git add`したときにこんながでたら(CRLF:改行コードの一種らしい。)
 - warning: LF will be replaced by CRLF in /~~/~~.rb. The file will have its original line endings in your working directory.

`$ git config --global core.autoCRLF false`

- `$ rake generate migrate 名前`でマイグレート ファイルを作成後、change_column_defaultを追加する
 - 参考
  - [Rails のマイグレーションで、DBテーブルのカラムのオプションを変更する](http://easyramble.com/change-column-options-migration.html)
  - [カラムの初期値を設定(change_column_default)](http://railsdoc.com/migration#%E3%82%AB%E3%83%A9%E3%83%A0%E3%81%AE%E5%88%9D%E6%9C%9F%E5%80%A4%E3%82%92%E8%A8%AD%E5%AE%9A(change_column_default))



***
chrome & firefox 開発ツール `Ctrl + Shift + I`

Internet Explorer 開発者ツール　`F12`

- [登録静的](http://railstutorial.jp/chapters/filling-in-the-layout?version=4.0#sec-user_signup)

- [登録動的](http://railstutorial.jp/chapters/sign-up?version=4.0#top)



- [has_many](http://railstutorial.jp/chapters/a-demo-app?version=4.0#sec-demo_user_has_many_microposts)

- [postgresql文書](http://www.postgresql.jp/document/9.2/html/index.html)

- [rails console コマンド](http://railsdoc.com/rails)
