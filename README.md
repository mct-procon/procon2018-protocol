# procon2018-protocol
第29回全国高等専門学校プログラミングコンテスト 人力部門 Protocol between AI and interface. Developerd by 松江高専, Go Suzuki.

# 概要
インターフェースとAI間をプロセス間通信でつなぐライブラリです．データのシリアライズ/デシリアライズには，MessagePack-CSharpを使用しています．TCPで通信するため，少しコードを変更すれば，別のPC同士をつなげることもできます．  

# 環境
.Net Standard 2.0  

# ディレクトリ構造
\[DIR]Methods -- インターフェース-AI間のメソッドのデータ構造の定義  
\[DIR]AIFramework -- AIを簡単に実装するためのフレームワーク  
IPCManager -- プロセス間通信を管理するクラス  
IIPCReader -- メソッドが呼ばれたときに実行されるメソッドを定義するためのインターフェース  
