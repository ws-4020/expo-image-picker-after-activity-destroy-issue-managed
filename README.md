# expo-image-picker-after-activity-destroy-issue-managed

以下の手順でカメラが起動することを確認

* Androidの開発者オプションで、「Don't keep activities」を有効にする
* `npm run android`でアプリ起動
* カメラ起動
* アプリをバックグラウンドに移動
* アプリをフォアグラウンドに移動
* カメラ起動

## 検証ページを作成するまでに実施したこと

* `npx create-expo-app [PJ名]`でPJ作成
* `expo install expo-image-picker`を実行してexpo-image-pickerをインストール
* `npm run android`を実行
