# learn-github
マージとかプルリクとか試してみる勉強用のリポジトリ。


# GitHubとGitを連携する

### リモートリポジトリをローカルにクローン
プロジェクトディレクトリを置きたいディレクトリで以下のコマンド

`git@github.com~`の部分はリポジトリページ右上のCodeからコピペ。

```
git clone git@github.com:devtoku/learn-github.git
```

### リモートリポジトリをローカルのリモート追跡ブランチに反映
リモートリポジトリの最新の状況(ブランチとか更新履歴)だけをローカルの情報に反映させる。

```
git fetch origin main
```

### リモート追跡ブランチの情報をローカルに反映
あああああ！

```
git merge <commit>
```

### fetchとmergeを同時にするpull
pullは上記2つの動作を同時に行う

```
git pull origin main
```