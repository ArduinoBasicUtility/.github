# ArduinoBasicUtility


比較的汎用性が高いライブラリや他のアプリケーションのテンプレートに使えるアプリケーションを集めたもの．


## マルチアーキテクチャ対応ライブラリ
主に，MCUの違いや機種の違いを吸収するためのライブラリ．

- [detectArduinoHardware](https://github.com/ArduinoBasicUtility/detectArduinoHardware) : コンパイル時にArduinoの機種を区別するヘッダファイル
- [arduinoHardwareHelper](https://github.com/ArduinoBasicUtility/arduinoHardwareHelper) : ソフトウェアリセットやデジタルポートがPMW対応か否かを判定するAPIを提供
- [UniSleep](https://github.com/ArduinoBasicUtility/UniSleep) : Arduinoおよびその互換機(全てではない)でCPUを止めてsleepさせる統一的なAPIを提供するライブラリ
- [NiUtils](https://github.com/ArduinoBasicUtility/NiUtils) : Arduinoでネットワークを使う場合，機種やネットワークコントローラチップの違いで発生する「#ifdefの山」を削減するためのライブラリ


## 汎用性が高い機能のライブラリ
- [ArduinoPassword](https://github.com/ArduinoBasicUtility/ArduinoPassword) : SDに入っているパスワードファイルを用いて，ユーザ認証を行うライブラリ
- [Syslog](https://github.com/ArduinoBasicUtility/Syslog) : syslogのライブラリ
- [dateUtils](https://github.com/ArduinoBasicUtility/dateUtils) : 時刻情報のデータ型，UNIXエポックタイムを取り扱うためのライブラリ
- [IntString](https://github.com/ArduinoBasicUtility/IntString) : 文字列と数の相互変換のライブラリ
