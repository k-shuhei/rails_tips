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

