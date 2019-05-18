# PaSoRich - PaSoRi with Scratch 3.0
Scratch3.0でSONY PaSoRi (RC-S380) を使ってFelicaのIDmを読み取るための拡張機能です。［注意：まだ開発段階］

手元にある様々なFelicaカードを使ったプログラムの開発が可能になることを目指しています。

---

## 必要なもの
- SONY PaSoRiカードリーダー（RC-S380のみ対応）
- Google Chrome（WebUSB対応するブラウザのみ）
- Felicaカード
- Scratch 3.0

---

## 開発状況
WebUSBによる動作実験段階です。

ローカル環境だと動作するものの，サーバー経由だとWebUSB「navigator.usb.requestDevice」が動作しない問題がある模様。

ローカル環境では，カード読み取りは可能であるものの，読み取ったIdmの反映に1秒程度待機が必要です。ブロックの構成見直し中。

## 開発環境
macOS上でローカルScratch3.0環境を構築して開発。
他のプラットフォームでの動作は未確認。

## 参考情報

[SONY PaSoRi RC-S380](https://www.sony.co.jp/Products/felica/consumer/products/RC-S380.html)

[Scratch 3.0の拡張機能を作ってみよう](https://ja.scratch-wiki.info/wiki/Scratch_3.0の拡張機能を作ってみよう)

[WebUSBことはじめ - Qiita](https://qiita.com/Aruneko/items/aebb75feca5bed12fe32)

[WebUSBでFeliCaの一意なIDであるIDmを読む - Qiita](https://qiita.com/saturday06/items/333fcdf5b3b8030c9b05)

[How to Develop Your Own Block for Scratch 3.0](https://medium.com/@hiroyuki.osaki/how-to-develop-your-own-block-for-scratch-3-0-1b5892026421)

