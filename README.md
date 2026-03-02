# ワンストップアウトプット！公式ガイドブック

2026年4月4日開催のアウトプットの背中を押すカンファレンス　「ワンストップアウトプット！」の公式ガイドブックのリポジトリです。

実行委員会のガイドブック作業と、登壇者／参加者の寄稿記事の編集作業に使います。

Push権限付けることも可能。

## 前提

* [Node.js](https://nodejs.org/en/)

## install

```sh
npm i
nmp intall @vivliostyle/vfm
```

## 本を作成

本を作成するコマンドは `npm run build` と `npm run build:print` です。

```sh:オンラインで使う前提のカラーPDFを作成するコマンド
npm run build
```

```sh:印刷対応の、なるべく白黒に寄せたPDFを作成するコマンド
npm run build:print
```

## プレビュー

```sh
npm run preview
```
## 本文の書き方
chap-introduction.mdと
chap-template.mdを見てください。

また、vivliostyle.config.jsにファイル名を追加するのを忘れないようにお願いします。

Push／Mergeすると、Actionsが走って自動でpdfがビルドされます。
Actionsの一番新しいやつを確認してみてください。
保存期間は3日です。

## ライセンス

* `src/*` は原稿ファイルと画像ファイルなのでオープンソースとしてのライセンスは付与しません。
* サンプルコードは普通に使っていただいてかまいません
* それ以外のファイルはMIT Licenseのもと使っていただいてかまいません。設定ファイルには筆者の名前や、この本のタイトルなどが書かれいているためご自身の物に書き換えることは忘れないでください。

### 使用しているフォントのライセンス

License: SIL Open Font License, Version 1.1.

* https://github.com/microsoft/cascadia-code
* https://github.com/IBM/plex
* https://github.com/trueroad/HaranoAjiFonts
