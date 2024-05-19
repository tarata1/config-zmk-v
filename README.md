## bluetooth対応corne
- 5個のbluetooth接続プロファイルを保持
- 有線接続も可能
- LiPoバッテリーを搭載し、繰り返し充電可能 
- ロータリーエンコーダ搭載


## 電源スイッチ
- 電源スイッチは下記写真の〇印の箇所にあります。上がON,下がOFFです。
<img width="544" alt="sw" src="https://github.com/tadanaka/test/assets/168345103/5ea64c33-08e8-4d5f-b062-095fe33222ba">


## LED点灯
- 電源スイッチは下記写真の〇印の箇所にあります。
 <img width="544" alt="led" src="https://github.com/tadanaka/test/assets/168345103/b78f4ed4-689e-4280-8033-439a29e60fc2">

- 電源投入時に２度点滅します
- 1回目　バッテリー残量　グリーン：100～80％　　イエロー：80～20％　　レッド：20～0％
- 2回目　bluetooth接続状態　　ブルー：接続完了　　イエロー：未設定　　　レッド：未接続


## 注意事項
- 充電する際は、スイッチONの状態で行ってください。
- 左手キーボードはバッテリー充電中にbluetoothとデバイスとの接続が遮断されます。充電しながらキーボードを使用したい場合は、使用するデバイスと有線接続で利用して下さい。
- bluetooth接続プロファイルはキーボード上で選択、削除ができます。

- 
## キーマップの変更方法

- このリポジトリをフォークしてください。
- [キーマップエディタ](https://nickcoutsos.github.io/keymap-editor/)でgithubと連携後、キーマップを変更し、saveボタンを押してください。
- 5分程度経過するとフォームウェアの生成が完了しますので、![image](https://github.com/tadanaka/test/assets/168345103/dda6d494-b72d-4bc1-aa8f-3bf09780cb94)このボタンをクリックしてください。
- 画面下部へスクロールして `firmware.zip`をダウンロード及び解凍してください。
- キーボードをPCと接続し、写真の〇印にリセットボタンがあるので、ダブルクリックしてください。<img width="544" alt="reset" src="https://github.com/tadanaka/test/assets/168345103/74f45590-e012-42e3-bf16-e35bbbff8ee7">
- リセットボタンを押すことに慣れれば、爪楊枝やピンセット等を使用してカバーを外さずにダブルクリックができるようになります。しかし、最初はカバーを外して、そのカバーを使用してリセットボタンをクリックすることをお勧めします。
- ダブルクリックに成功すると、`XIAO-SENSE`という名前でドライブが認識されるので、作成したキーマップのフォームウェアを書き込んでいきます。
- 左のキーボードには`corny_left rgbled_adapter-seeeduino_xiao_ble-zmk`、右のキーボードには`corny_right rgbled_adapter-seeeduino_xiao_ble-zmk`を書き込んでください。
