# やったこと
- git init
 - カレントディレクトリを管理対象としてリポジトリを作成するコマンド．
 - ```.git```という隠しディレクトリが生成される．（リポジトリを削除したいときは，```.git```ディレクトリを削除すればOK）

- git add
 - Untracked, Modefiedな変更差分をStagedな状態にするコマンド．
 - ここで追加しておいたディレクトリ・ファイルが，後の```git commit```コマンドの対象となる．

- git branch
 - 引数なしならリポジトリにあるブランチのリストと，現在アクティブなブランチを教えてくれるコマンド．
 - ```git branch branch_name```:branch_nameという名前の新規ブランチを生成．
  - このコマンドを実行しても，branch_nameブランチに切り替えてくれるわけではないので，```git checkout```コマンドで切り替えが必要．
  - このコマンドの代わりに```git checkout -b branch_name```コマンドを実行することで，ブランチの作成と切り替えを同時にできるので，こっちを使うことが多い(らしい)．
 - ```git branch -d branch_name```:branch_nameブランチを削除．
 - ```git branch -D branch_name```:branch_nameブランチを__強制__削除．
 - ```git branch -m branch_name```:現在ブランチ名をbranch_nameに変更．
 - ```git branch -M branch_name```:現在ブランチ名をbranch_nameに__強制__変更．

- git checkout
 - ```-b```をオプションに指定することで，引数を新規ブランチとして作成し，切り替えることができる．
 
