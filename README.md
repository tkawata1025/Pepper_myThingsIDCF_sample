
IDCF Cloud を介して myThings と Pepper を連携させるサンプルボックスです。
HTTP リクエストにより Action, Trigger と連携するものと、MQTT にて IDCF Cloud に subscribe, publish するものとの４種類のサンプルボックスを提供します。

サンプルの中の MQTT ボックスは MQTT ライブラリ paho-mqtt が必要です。paho-mqtt ライブラリをプロジェクトに取り込むには Choregraphe プロジェクトディレクトリ myThings_IDCFCloud_sample の下で次を実行します。

pip install paho-mqtt --target ./lib --no-compile

IDCFCloud サーバの設定は次が参考になります。

http://qiita.com/masato/items/f9be4a15216fe29de7fb

****
提供物はすべてサンプルプログラムとお考えください。
耐久試験や、異常系の完全な動作確認テストは行っていません。
****

