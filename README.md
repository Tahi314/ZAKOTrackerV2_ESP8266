# ZAKOTrackerV2 - Sender (ESP8266)

自作VRモーショントラッカー「ZAKOTracker」V2のセンサーノード（送信側）ファームウェア。

各トラッカーノードに搭載されたBNO055 IMUからクォータニオンを取得し、ESP-NOWで受信側（ESP32）に送信します。

## 関連リポジトリ

- [ZAKOTrackerV2_ESP32](https://github.com/Tahi314/ZAKOTrackerV2_ESP32) - 受信側ファームウェア（ESP32）
- [ZAKOTrackerV2_Hardware](https://github.com/Tahi314/ZAKOTrackerV2_Hardware) - 基板設計データ（KiCad）

## 構成

- **マイコン**: ESP8266
- **センサ**: BNO055 IMU（I2C接続）
- **通信**: ESP-NOW（60Hz）
- **開発環境**: PlatformIO

## 参考

- [ZAKOTrackerV1.0の解説記事（Zenn）](https://zenn.dev/tahi_314/articles/8bd749271e5c29)

## ライセンス

MIT License
