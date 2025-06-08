## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。https://api.adviceslip.com/advice

* エンドポイントと機能
エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
機能：郵便番号（7桁）を指定することで、対応する住所をJSON形式で返すAPI。
* リクエストとレスポンスのフォーマット
https://zipcloud.ibsnet.co.jp/api/search?zipcode=1000001でリクエスト
レスポンスでJSONから取り出す
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
名称： Advice Slip API（アドバイス自動生成API）
URL： https://api.adviceslip.com/
* エンドポイントと機能
エンドポイント：https://api.adviceslip.com/advice
機能：呼び出すたびに、ランダムな英語のアドバイスを1件返す。
* リクエストとレスポンスのフォーマット
リクエスト：https://api.adviceslip.com/advice
レスポンス：JSONで返す
### Q3-3. 感想
* 今回の課題で苦労したこと
APIの登録利用方法やfetch()関数の書き方や、非同期処理を理解するのが少し難しかった。
* 演習を通して理解できたこと
JavaScriptでAPIと連携することで様々な機能を搭載できる利便性が理解できた
APIからのデータ取得について理解が深まった
* Web APIの利便性や課題など
APIは外部と連携して、比較的に少ないコードで情報を表示できるので便利だと感じた
エラー処理の追加が困難だったのでこれから気を付けたいと感じた


