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
***
chrome & firefox 開発ツール `Ctrl + Shift + I`

Internet Explorer 開発者ツール　`F12`

- [登録静的](http://railstutorial.jp/chapters/filling-in-the-layout?version=4.0#sec-user_signup)

- [登録動的](http://railstutorial.jp/chapters/sign-up?version=4.0#top)



- [has_many](http://railstutorial.jp/chapters/a-demo-app?version=4.0#sec-demo_user_has_many_microposts)

- [postgresql文書](http://www.postgresql.jp/document/9.2/html/index.html)

- [rails console コマンド](http://railsdoc.com/rails)
