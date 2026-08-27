# Git学習メモ
## Gitコマンド
### 初期設定
* Gitの初期設定を確認  
$ `git config --list`
* ユーザー名の登録  
$ `git config --global user.name ...`  
* メールアドレスの登録  
$ `git config --global user.email ...`  
* コミットメント入力用エディタをvsCodeに指定  
$ `git config --global core.editer "code --wait"`  
* デフォルトブランチ名をmasterではなくmainに設定  
$ `git config --global init.defaultBranch main`  
* Git初期設定を削除する方法  
$ `git config --glonal --unset ...`