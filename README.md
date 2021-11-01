# 手順

### 1. gitをクローンしてみよう！！

cd でファイルを作りたい場所に移動

![clone](screenshot/git_clone.png "clone")

コマンド
```
git clone https://github.com/oe1307/git_tutorial.git
```

※サーバー上で行うときは

Settings -> Developer settings -> Personal access tokens
からアクセストークンを行う必要がある

詳しくは [wiki](https://github.com/oe1307/git_tutorial/wiki) で



### 2． ブランチを立てる / ブランチに移動して開発を行おう！！

githubの大元である```master(旧名:origin)```には大事なコードが集まっているので，必ずブランチを立ててそこで開発を行う

![branch](screenshot/branch.png "branch")

実際にディレクトリ```tmp```に何かファイルを追加してみよう


### 3. add / commit /push をやってみよう

まずは，gitの状態を確認

```git status```

Changes not staged for commit:

もしくは

Untracked files:

と書かれているのが add されていないファイル

```git add <ファイルまでのパス>``` 

### 4. issue を立てる / pull requestを出してみよう!!

自分のTODOを```issue```にまとめて全体に共有する


### 5. pull してみよう！

最新の github の情報を受け取るにはpullを実行する必要がある

```git pull```

もしくは

```git pull origin <ブランチ名>```

### 6. ほかにも色々とあるので調べながら行う

