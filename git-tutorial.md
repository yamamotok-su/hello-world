gitは分散管理型のバージョン管理システムで元々はオープンソースソフトウェア管理のためのソフトウェアです
変更履歴が残る
変更した箇所に戻ることができる
他人と共同編集できる　        などの特徴があります

$ git config --global user.name "[name]"
    コミット操作に付加されるあなたの名前を設定します

$ git config --global user.email "[email address]"
    コミット操作に付加されるあなたのメールアドレスを設定します

$ git config --global color.ui auto
    コマンドラインの出力を見やすくするため色を設定できます

$ git init [project-name]
    指定した名前のローカルリポジトリを作成します

$ git clone [url]
    プロジェクトとすべてのバージョン履歴をダウンロードします

$ git status
    コミット可能なすべての新規または変更のあるファイルを一覧で表示します

$ git diff
    まだステージされていないファイルの差分を表示します

$ git add [file]
    バージョン管理のためにファイルのスナップショットを作成します

$ git diff --staged
    ステージングと最後のファイルバージョンとの差分を表示します

$ git reset [file]
    ファイルをステージングから外しますが、その内容は保持します

$ git commit -m "[descriptive message]"
    ファイルのスナップショットをバージョン履歴内に恒久的に記録します

$ git branch
    現在のリポジトリ上のすべてのローカルブランチを一覧で表示します

$ git branch [branch-name]
    新規ブランチを作成します

$ git checkout [branch-name]
    指定されたブランチに切り替え、作業ディレクトリを更新します

$ git merge [branch]
    指定されたブランチの履歴を現在のブランチに統合します

$ git branch -d [branch-name]
    指定されたブランチを削除します

git rm [file]
    作業ディレクトリからファイルを削除し、削除をステージします

$ git rm --cached [file]
    バージョン管理からファイルを削除して、ローカルのファイルは保持します

$ git mv [file-original] [file-renamed]
    ファイル名を変更し、コミットします

$ git stash
    すべての変更のあるトラックされているファイルを一時的に保存します

$ git stash pop
    直近に一時保存されたファイルを復旧します

$ git stash list
    すべての一時保存された変更セットを一覧で表示します

$ git stash drop
    直近に一時保存された変更セットを破棄します

$ git fetch [bookmark]
    リポジトリブックマークからすべての履歴をダウンロードします

$ git merge [bookmark]/[branch]
    ブックマークのブランチを現在のローカルブランチに統合します

$ git push [alias] [branch]
    すべてのローカルブランチのコミットをGitHubにアップロードします

$ git pull
    ブックマークの履歴をダウンロードし、変更を統合します