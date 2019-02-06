# __authz認証のサンプル(token)
OAuth認可エンドポイント(__authz)を使用してトークンを取得する為の実装のサンプルです。

# サンプル
https://demo.personium.io/samples-appdev/__/01_simplest_app_implicit_flow/html/sample.html

1.セルURLを入力します。
1.GetTokenボタンを押下し、認証ページが表示されます。(認証がされてない場合に__authzが表示するページです。既に認証済みの場合表示されません。)
1.認証後、アプリセル(samples-appdev)から認証されたトークンを取得します。
※前提条件として、入力するセルにはアプリセル(samples-appdev)に紐づくBOXを作成しておく必要があります。