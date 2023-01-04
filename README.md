# CREATE 教育 GitHub 演習

## このドキュメントの目標
 - git & GitHubがvscodeを通じて使えるようになる

## 環境構築
### GitHubに登録
[GitHubへのリンク](https://github.com) へアクセスし、ユーザー登録を行う。

### vscodeのインストール
[vscodeのインストール先のURL](https://code.visualstudio.com/download) からvscodeをインストール、右クリックメニューに登録しておくと便利

### gitのPCへのインストール
1. [gitのインストール先のURL](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) からgitをインストール。

1. 次に、[GitHubのEmail設定へのリンク](https://github.com/settings/emails)にアクセス、`Primary email address`の欄に`@users.noreply.github.com`のアドレスがあるのでそれをコピーしておく。`Ctrl +F`コマンドで探すと一発で見つかる。

1. 以下のコマンドを`Powershell`もしくは`Git Bash`で実行、`<email>`は先ほどコピーしたものを使用する。`<name>`は自由。両者の前後の`"`は忘れると失敗するので注意。

```
git config --global user.name "<name>"
git config --global user.email "<email>"
```

## GitHub で開発を行う手順の演習




MIT License

Copyright (c) 2023 Yuto Noguchi (CREATE)