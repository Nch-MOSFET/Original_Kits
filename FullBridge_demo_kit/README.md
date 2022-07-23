# FullBridge_demo_kit

## Description

- フルブリッジインバータを模擬したキットです。押し方によってLEDの光り方が変わります。また、信号取り出し用のピンソケットも付いています  
- 電源は7V ~ 30Vに対応していますが、リニアレギュレータの発熱の都合上15Vまでの範囲で使用することを推奨します。006Pバッテリなどを接続してお使いください  
- 電源入力部に逆接続保護用のダイオートを接続しているため万が一電源を逆接してしまっても保護できます
- 縦に並んでいるスイッチ（SW1とSW2、またはSW3とSW4）が同時に押されている状態、いわゆるレグショートになっても回路が壊れないように短絡保護抵抗が付いていますが、なるべくショートしないようご注意ください
- Cタイプ基板と同じ大きさになっています

## Parts

基本的にすべての部品を秋月電子の通販サイトにて購入できます

| 部品番号 | 部品名 | 定数 | 秋月電子通販コード |
|----|----|----|----|
| J1 | 電源用ターミナル | 2端子 | [P-01306](https://akizukidenshi.com/catalog/g/gP-01306/) |
| J2 | 信号出力端子 | 2端子 | [C-10097](https://akizukidenshi.com/catalog/g/gC-10097/) |
| D1 | 逆接保護ダイオード | 1000V1A | [I-13561](https://akizukidenshi.com/catalog/g/gI-13561/) |
| D2 | 発光ダイオード | 緑色 | [I-06405](https://akizukidenshi.com/catalog/g/gI-06405/) |
| D3 | 発光ダイオード | 赤色 | [I-04111](https://akizukidenshi.com/catalog/g/gI-04111/) |
| C1 | 電源入力コンデンサ | 220μF35V | [P-11758](https://akizukidenshi.com/catalog/g/gP-11758/) |
| C2 | 電源入力コンデンサ | 1μF50V | [P-08150](https://akizukidenshi.com/catalog/g/gP-08150/) |
| C3 | 電源出力コンデンサ | 1μF50V | C2と同一 |
| C4 | 電源出力コンデンサ | 220μF35V | C1と同一 |
| U1 | リニアレギュレータ | 5V1.5A | [I-08678](https://akizukidenshi.com/catalog/g/gI-08678/) |
| R1 | 短絡保護抵抗 | 3W100Ω | [R-11019](https://akizukidenshi.com/catalog/g/gR-11019/) |
| R2, R3 | LED保護抵抗 | 1/4W470Ω | [R-25471](https://akizukidenshi.com/catalog/g/gR-25471/) |
| SW1 ~ SW4 | タクタイルスイッチ | 1回路1接点 | [P-03647](https://akizukidenshi.com/catalog/g/gP-03647/) |
|  | スペーサ | M3 | [P-01864](https://akizukidenshi.com/catalog/g/gP-01864/) |

※部品によっては複数個セットで販売されています

## 基板イメージ

部品取り付けの際の参考にどうぞ  
J1のみ3Dモデルがなかったため欠けています

上面から:
![image](https://user-images.githubusercontent.com/91242561/180594928-08f13818-89d4-405c-ae28-f26ba7474fc1.png)

横面から:
![image](https://user-images.githubusercontent.com/91242561/180594956-5ac7223b-0a22-48a2-b2dc-ca7890f41c49.png)
![image](https://user-images.githubusercontent.com/91242561/180594965-d392adf4-7744-40f8-803d-43c52a862aa8.png)
![image](https://user-images.githubusercontent.com/91242561/180594973-1f4f23ba-825c-4abe-9530-6a02924398c0.png)
![image](https://user-images.githubusercontent.com/91242561/180594974-587636fd-844b-4c9c-8396-ba7890e29064.png)

底面から:
![image](https://user-images.githubusercontent.com/91242561/180595063-4cbe9989-8b1d-4902-b820-b53e281cc6f5.png)

## 回路図

![image](https://user-images.githubusercontent.com/91242561/180596170-118ee0aa-1ead-401e-93a7-713290e4feeb.png)
