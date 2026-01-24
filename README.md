# Git・Pull Request 活用プラクティス

コーディングを進めるにあたり、Git・Pull Requestの活用方法を学ぶための練習用リポジトリです。


## 課題1: Pull Request の問題点を発見する(1)

[PR #1](https://github.com/fjordllc/git_recipes/pull/1) について、問題点を指摘してください。

## 課題2: Pull Request の問題点を発見する(2)

[PR #2](https://github.com/fjordllc/git_recipes/pull/2) について、問題点を指摘してください。

## 課題3: 履歴の調べ方を確認する

`recipes/teriyaki.html` 内の「しょうゆ」という表記は、以前は「醤油」と書かれていましたが、とある理由により漢字をひらくように変更されました。
この変更が入った理由を、GitHub上のBlameを使って探してください。

## 課題4: 実際によい Pull Request を作る体験をする

「肉じゃが」のレシピに対して、次のような意見が挙がったので、対応することになりました。
このリポジトリをForkして、自身のリポジトリにて下記を解決する Pull Request を作成してください。
今回のcommitの際には、1変更1commitの粒度で対応してください。

- 肉じゃがの写真が大きすぎるので、最大の横幅を 300px になるように制限する
- 「白滝」の表記がわかりにくいので、「しらたき」に変更する
- ポイントの記載sectionに `class="tips"` を適用する


# 補足・提出方法

## 課題1・2

FBCの提出物のページに回答を記載してください。

## 課題3

変更理由を示すcommitのURLを提出してください。

## 課題4

下記の方法で作成したPull RequestのURLを提出してください。

1. 右上の Fork ボタンを押してください。
2. #{自分のアカウント名}/git_recipes が作成されます。
3. 作業PCの任意の作業ディレクトリにて git clone してください。

```
$ git clone https://github.com/自分のアカウント名/git_recipes.git
```

4. ブランチを**main**ブランチから作ってください。例えば以下のようにします。

```
$ git switch -c fix_nikujyaga main
```

5. 課題で提示されている変更をcommitしてください。

6. 完成したら、Pull Requestを作成し、URLを提出してください。
Pull Requestの作成画面では、merge先として **自分自身のアカウントのgit_recipesリポジトリ** を指定してください。
また、**作成したPull Requestは提出後に確認OKをもらうまでmergeのボタンを押さないでください。**
![Pull Request作成画面](https://github.com/user-attachments/assets/e3bd4b7e-951d-438a-a65b-45dadb26eb85)
