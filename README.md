# ChannelBreakoutBot
## 使い方
configファイルにBitmexのAPIキーを入力後，`python trade.py`で実行．時間足は1分から60分，またはそれ以降まで．`isTest`でBitmexかBitmex Testnetで行うかを判断．

## 戦略
タイトル通り，チャンネルブレイクアウト戦略を用いてます．1時間足18期間が強いらしいです．ドテン売買で行います．

## ローソク足の取得に関して
こちらの[Note](https://note.mu/nagi7692/n/n402026839b39)にあるソースコードに少しだけ手を加えました．[@Nagi7692](https://twitter.com/Nagi7692)さんに感謝です．

## 注意点
本ソフトウェアで被った損害は一切保証しません．

## Lisence
MIT
