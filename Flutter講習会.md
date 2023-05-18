# Flutter講習会

## 勉強すること
* Riverpod
* Firebase
* go_router
* ThemeData
* 種々のWidget
  mainAxisAlignment, crossAxisAlignment
* ディレクトリ構造
* Live Template
* Android Studio ショートカットキー
* メンテナンス性について
* Firestore, read有利, write有利
  users/<user>/posts/<post>
  posts/<post>
  CollectionGroup で取得できるっぽい
* Firestoreのセキュリティ
* Firestoreの制限を知っておこう
  きちんと設計しないと書き込み制限やwhereの制限に引っかかる。バグの元。富士通のあの件みたいになる
  https://qiita.com/1amageek/items/d606dcee9fbcf21eeec6
  https://qiita.com/1amageek/items/343f262ba3b50e657078
* 

## TODOアプリの修正点
* Navigator -> go_router
* My~~App -> MyApp
* Pageごとにファイルに分ける
* Container(padding: ) -> Padding(padding: )
* ログインフォームで Form() ウィジェット, validator
* Firebase Authでメールログイン以外も使う
* Userのアイコン
* FieldValue.serverTimestamp()
* Firestore Realtime Update

## どんなアプリを作るか
### ドラフト
* TODOアプリ
  Firebase Storage使えない・・・
  TODOに画像を添付できる
* TODO共有アプリ
  ユーザーグループでTODOをシェアできる
  TODOには画像を添付できる
  TODOにメッセージ
* AIがいるSNS(インスタ,Twitterもどき)
  functionsの練習
  フォロー
  Like
  返信

### 本企画
* Firebase Authでログイン
  メールとGoogle
* HomePageでToDo一覧表示
* ToDoには以下の情報が付いている
  - タイトル
  - 詳細
  - 添付画像
  - updatedAt, createdAt
  - 

## Codelabの進め方
このCodelabで勉強できることの紹介
UI作成
Firebase参照
riverpodで状態管理
go_router