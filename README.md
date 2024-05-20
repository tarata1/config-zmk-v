## bluetooth対応ロータリーエンコーダ付きcorne
- フォームウェアにZMKを使用
- 5個のbluetooth接続プロファイルを保持
- 有線接続にも対応。
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


## 特記事項
- 充電する際は、スイッチONの状態で行ってください。
- 左手キーボードはバッテリー充電中にbluetoothとデバイスとの接続が遮断されます。充電しながらキーボードを使用したい場合は、使用するデバイスと有線接続で利用して下さい。他のデバイスやコンセントで充電している間は使用不可となります。
- bluetooth接続プロファイルはキーボード上で選択、削除ができます。


## キーマップの変更方法

- このリポジトリをフォークしてください。
- [キーマップエディタ](https://nickcoutsos.github.io/keymap-editor/)でgithubと連携後、キーマップを変更し、saveボタンを押してください。
- 5分程度経過するとフォームウェアの生成が完了しますので、![image](https://github.com/tadanaka/test/assets/168345103/dda6d494-b72d-4bc1-aa8f-3bf09780cb94)このボタンをクリックしてください。
- 画面下部へスクロールして `firmware.zip`をダウンロード及び解凍してください。
- キーボードをPCと接続し、写真の〇印にリセットボタンがあるので、ダブルクリックしてください。<img width="544" alt="reset" src="https://github.com/tadanaka/test/assets/168345103/74f45590-e012-42e3-bf16-e35bbbff8ee7">
- リセットボタンを押すことに慣れれば、爪楊枝やピンセット等を使用してカバーを外さずにダブルクリックができるようになります。しかし、最初はカバーを外して、そのカバーを使用してリセットボタンをクリックすることをお勧めします。
- ダブルクリックに成功すると、`XIAO-SENSE`という名前でドライブが認識されるので、作成したキーマップのフォームウェアを書き込んでいきます。
- 左のキーボードには`corny_left rgbled_adapter-seeeduino_xiao_ble-zmk`、右のキーボードには`corny_right rgbled_adapter-seeeduino_xiao_ble-zmk`を書き込んでください。

  ## デフォルトレイヤーの一覧
- ロータリーエンコーダの押し込みも１つのキーとして認識されます。例えば、初期レイヤ―では左手のロータリエンコーダは、取り消し,やり直しが登録されていますが、押し込みながら操作するとことでブラウザでの進む，戻るの操作が可能となっています。
- コンボという2キー以上の同時押しによるキー割り当てがあり、D,F同時押しで半角英数字入力J,K同時押しでひらがな入力としています。
- レイヤー2にbluetooth設定のキー配置をしています。BT_SEL0～4の切り替えで接続先デバイスの切替が可能で、BT_CLTにてプロファイル削除が可能です。

- 初期レイヤー
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/19bf16c6-8f26-4089-8299-4e8c92263105)
- レイヤー1
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/d885dab9-d509-4021-90a8-4b634ad9ac0a)
- レイヤー2
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/b706e26e-55e8-479e-93d3-bed3732f5396)
- レイヤー3
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/f80cbc93-9624-4e2d-8153-3cf302c16538)
- 英数
  
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/b6547a28-0012-4da0-9296-b720e02214eb)
- かな
  
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/80ae9fe0-c29c-4573-8757-47135ff50db9)
- テンキー(レイヤー3)移行
  
![image](https://github.com/tadanaka/config-zmk-v/assets/168345103/9f1cab6e-a79e-4b27-8951-072442dd310e)
