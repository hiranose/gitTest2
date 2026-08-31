# Gitコマンド学習メモ
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
### コミット操作
* ローカルリポジトリの初期化 
$ `git init` 
* 現在の状態を見る 
$ `git status` 
* コミットしたいファイルを、先にステージングエリアに追加 
$ `git add <ファイル名>` 
* ステージングエリアにあるファイルのコミット
$ `git commit` 
* 同ファイルのコミット(コマンドと一緒にコミットメッセージを入力) 
$ `git commit -m "コミットメッセージを入力"` 
### ブランチ操作
* ブランチ一覧を表示 
$ `git branch` 
* 新しいブランチを作成 
$ `git branch <ブランチ名>` 
* ブランチを切り替え 
$ `git switch <ブランチ名>` 
* ブランチの作成と切り替えを同時に行う 
$ `git switch -c <ブランチ名>` 
* ブランチをマージ 
$ `git merge <ブランチ名>` 
* マージ済みブランチを削除 
$ `git branch -d <ブランチ名>`