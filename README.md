# gaq-releases

GaQ Offline Transcriber（Windows 版、Microsoft Store で配布）の公開用リポジトリです。

## version.json

GaQ の「更新を確かめる」ボタンは、押されたときだけ次の URL を読みます。

https://yoshihito-tsuji.github.io/gaq-releases/version.json

- `latest`: Microsoft Store で公開中の最新の版（X.Y.Z）
- `released`: その版がストアで公開された日
- `schema`: このファイルの形式の版

ストアで新しい版が公開されてから書き換えます。審査中の版は書きません。
アプリは版の番号だけを読み、更新そのものは Microsoft Store に任せます。
