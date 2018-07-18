# odakasangyo2018
LINE botを開発するまで

## Atom(テキストエディタ)のインストール

テキストエディタというのは、要はメモ帳ですが、プログラムを書きやすいように構文チェックなどをしてくれたりする開発用のテキストエディタをインストールします。

Atomが比較使いやすくい

学校ではインストールできないため、Portable版を使います。

## Gitのインストール
学校ではインストールができないため、Portable版を使います。

## NodeJSのインストール
javascriptでサーバーを動かすためのライブラリー「NodeJS」をインストールします。

学校ではインストールができないため、ファイルを配置してコマンドラインでPATHを通しています。


### PATH通したりコマンドライン
・PATHを通す
・proxyを通す（nodeコマンド、gitコマンド）

set PATH=<PortableGitフォルダまでのパス>;<nodeフォルダまでのパス>;%PATH%;
call npm -g config set proxy http://proxy1.ut.fks.ed.jp:8080
call npm -g config set https-proxy http://proxy1.ut.fks.ed.jp:8080
git config --global http.proxy http://proxy1.ut.fks.ed.jp:8080
cmd
