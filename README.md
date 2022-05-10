# QooLee

QooLee is a keyboard with a 30% layout with ISO Enter.  
It can also be equipped with a rotary encoder.  
It supports hot-swapping of keyswitches with MX sockets and mounting of LEDs.  
VIA (Remap) firmware is also available.  

QooLeeはISO Enterを搭載した30%レイアウトのキーボードです。  
ロータリーエンコーダを搭載することも可能です。  
MXソケットによるキースイッチのホットスワップや、LEDの搭載にも対応しています。  
VIA(Remap)ファームウェアも用意されています。  


![image](https://github.com/takashicompany/qoolee/blob/master/images/01.jpg?raw=true)



## 必要な部品

### キットに同梱されているもの
|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|トッププレート|1||
|ボトムプレート|1||
|ダイオード（リードタイプ)|35||
|m2スペーサー(7mm)|6||
|m2ネジ(5mm)|12||
|リセットスイッチ|1||
|滑り止めシール|6||

### ご自身で用意が必要なもの
|部品|個数|備考|
|:--|:--|:--|
|キースイッチ|35|Cherry MX互換のもの。|
|キーキャップ|35|左のシフトキーは2uのものを採用しています。|
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### オプション
|部品|個数|備考|
|:--|:--|:--|
|コンスルー|1||
|MXソケット|35||
|WS2812B|6|アンダーグロウライトとしてキーボードの底面を光らせることができます。|
|2uスタビライザー|2||
|ロータリーエンコーダ|1||

##　組み立て方

組み立ての手順は、[Center x Enter](https://github.com/takashicompany/center_enter)と同様です。  
手順については、[千葉千夏/あずさん](https://twitter.com/azulee)の[自作キーボードキット「Center x Enter」を組み立てました（ビルドログ・ハードウェア編）](https://note.com/azulee/n/nbe20617f434b)をご覧ください。  
(一部の部品の個数は異なります)

## ファームウェアについて
ソースコードは[QMK Firmwareにマージ済み](https://github.com/qmk/qmk_firmware/tree/master/keyboards/takashicompany/qoolee)です。  
[Remapでのファームウェアの書き込み](https://remap-keys.app/catalog/XDEYpuBml3mIhoFDDAFg/firmware)にも対応しております。

ファームウェアの書き込み手順は[千葉千夏/あずさん](https://twitter.com/azulee)の[自作キーボードキット「Center x Enter」を組み立てました（ビルドログ・ソフトウェア編）](https://note.com/azulee/n/n8557fdfbc679)をご覧ください。

## 完成したら

### 13. 完成したら...

完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。
Twitterのハッシュタグは [`#QooLee #自作キーボード`](https://twitter.com/search?q=%23%E8%87%AA%E4%BD%9C%E3%82%AD%E3%83%BC%E3%83%9C%E3%83%BC%E3%83%89%20%23miniZone&src=typed_query) を付けていただけると幸いです。
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければ回答できるかと思います。
