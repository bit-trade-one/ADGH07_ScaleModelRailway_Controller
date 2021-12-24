# よくある質問


## Q: 付属のUSBシリアルモジュールとボードとの接続端子がわからない
### A: 下記のように接続ください。
 | 実験ボード(本製品ADGH07) | コード | シリアル変換モジュール | 
 | --- | --- |  --- |
 | RTS  | - | DTR | 
 | RXD  | - | RXD | 
 | TXD  | - |  TXD | 
 | VCC  | - |  VCC | 
 | CTS  | - |  CTS | 
 | GND  | - |  GND | 
 
----

## Q: シリアルモジュールのLEDインジケータの内容について教えてください。
### A: 下記画像を参照ください。  
![LED01](https://github.com/bit-trade-one/ADGH07_ScaleModelRailway_Controller/blob/master/image/image-Dec-01-2020-01-52-54-68-AM.png) 

----

## Q: ArduinoIDEから書き込みができない。
### A: 書き込みボードはArduinoUNOを選択したか・選択したCOMポートは正しいかをご確認ください。
COMポートの確認方法は下記のとおりです。  
付属のUSBシリアル変換モジュールをPCに接続し、  
Windows10の場合左下のWindowsマークを右クリックし、デバイスマネージャーを起動してくだい。  
表示項目の「ポート(COMとLPT)」の前の＞をクリックし  
ポート接続状況を確認ください。  
USB to UART Bridge (COM〇〇)  
の〇〇が本デバイス鉄道模型実験ボードとの通信に使用するCOM番号です。こちらを控えてarduinoIDEより接続ください。  
