# slack-bot-app

 # 目標
 ICカードリーダから学生証の情報を読み込み、gから始まる学生番号をtextboxに読み込ませ、入室退室のトリガーとする
 AWSへの通信プロトコルはHTTPで、hidden要素に学生番号と入室か退室のflg(2値)情報を送り込む

## ディレクトリ構造
### manifests
- [AndroidManifests.xml](https://github.com/ShotaArima/slack-bot-app/blob/main/app/src/main/AndroidManifest.xml) : このアプリに必要な設定ファイルが記述されている
## java
- [Android_Test](https://github.com/ShotaArima/slack-bot-app/tree/main/app/src/androidTest) : Androidアプリをテストするための.javaファイル
## res
Androidアプリの実行にひつようなファイル類で、.java以外のものを格納するフォルダです。
- [drawable](https://github.com/ShotaArima/slack-bot-app/tree/main/app/src/main/res/drawable) : 画像を格納
- [layout](https://github.com/ShotaArima/slack-bot-app/tree/main/app/src/main/res/layout) : 画面構成にかかわる.xmlファイルを格納
- [mipmap](https://github.com/ShotaArima/slack-bot-app/tree/main/app/src/main/res) : アプリのアイコンを格納
- [values](https://github.com/ShotaArima/slack-bot-app/tree/main/app/src/main/res/values) : 細かな指定をすることのできるファイル
  - [strings.xml](https://github.com/ShotaArima/slack-bot-app/blob/main/app/src/main/res/values/strings.xml) : 固定文字列の情報を格納
  - [themes.xml](https://github.com/ShotaArima/slack-bot-app/blob/main/app/src/main/res/values/themes.xml) : 画面テーマの情報を格納
  - [colors.xml](https://github.com/ShotaArima/slack-bot-app/blob/main/app/src/main/res/values/colors.xml) : 色構成の情報の格納
