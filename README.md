# Original_Kits

自作のキット基板のガーバーデータとドキュメントを公開するリポジトリです。基本的に自由に使っていただいて構いませんが事前に連絡をお願いします。こちらからどうぞ→[Twitterダイレクトメッセージ](https://twitter.com/messages/compose?recipient_id=1358261719701721088)  
ただし営利目的での利用はおやめください

詳細については[コンテンツ](#contents)にある一覧とリンク先のREADMEファイルをご覧ください

# Contents

- [FullBridge_demo_kit](./FullBridge_demo_kit)
  - フルブリッジインバータを模擬したキットです。押し方によってLEDの光り方が変わります。また、信号取り出し用のピンソケットも付いています

# In preparation

- Arduino_Lchika_Board
  - ArduinoのGPIOすべてにLEDを接続したボードです。マイコンプログラミングの基礎「Lチカ」にご使用いただける他GPIOの動作を可視化することもできます
  - Nano, UNO, Seeed Xiao用を公開予定です
- Multivibrator
  - 非安定マルチバイブレータの回路です。単三乾電池3本で動作します
- PicoTrafficLight
  - RP2040搭載マイコン Raspberry Pi Pico を使用した信号機のデモキットです。車両用と歩行者用を2方向分実装可能で、全てのLEDをGPIO経由で直接操作可能です
