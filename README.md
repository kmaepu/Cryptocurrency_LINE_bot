# Cryptocurrency_LINE_bot

　仮想通貨の現在価格を教えてくれるLINE botです。
 
 　バックグランド処理を[Node-RED](https://nodered.jp/docs/getting-started/)で構築しています。
  
# flow.jsonファイル

 Node-REDのフローが記述されたファイルです。Node-REDにインポートすると使用することができます。
 
 読み込むと次の図に示すフローが展開されます。
 
 ![全体フロー](https://user-images.githubusercontent.com/44369929/116424885-d7828b80-a87c-11eb-905d-8931d0baeaf0.JPG)
 
## 設定

　フローをインポートした後、CoinMarketCAP APIのkeyを設定します。
 
 　「httpリクエストのbody作成」ノードを開き、**API_KEY**の変数にCoinMarketCAP APIのkeyを入力します。
  　次の図に設定個所を示します。
 
 ![API_key](https://user-images.githubusercontent.com/44369929/116427059-a60abf80-a87e-11eb-9f4e-8f133aba30a9.JPG)


  
  
