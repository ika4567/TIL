#### DWC チャレンジ学習フェーズ12章
(2022.5.20)

## Ajaxを学ぶ

- **Ajax** （Asynchronous JavaScript +XML）は、JavaScriptを使って非同期にサーバー間での通信を行う。
- 仕組みは、  
クリックなどのイベントが起こる  
→「API」を使ってサーバーに**リクエスト** を送る（非同期通信）  
→リクエストされた情報の処理をサーバー側で行う  
→処理の結果を「JSON」形式でクライアントに送信  
→**レスポンス** の結果でページが更新される
- **Web API** は、WebサーバーやWebブラウザ用のAPI。  
必要なURLを入力して「リクエスト」を行い、その「レスポンス」として結果を受け取っている。
- **JSON** はテキストベースのデータ交換フォーマット。  
「リクエストとレスポンス」を行うにあたり、クライアント（人）とサーバー（マシン）が互いに理解できるデータ形式に変換するのに利用されている。
- **$.ajax()** はAjaxを実装するメソッド。
- $(‘#id名’).text(JSONから欲しい値) とすることで、指定したidのテキストをJSONから受け取った形に玄関できる。
- **$(要素名).attr(属性, 値);** と指定すると、指定した要素に属性が追加される。  
※タブメニュー作成時は属性の取得に使用。今回は属性の設定に使用。

[HTMLファイル](https://github.com/ika4567/DWC_java/blob/main/Ajax-Lesson/index.html)  
[jsファイル](https://github.com/ika4567/DWC_java/blob/main/Ajax-Lesson/script.js)