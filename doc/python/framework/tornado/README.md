# tornado
## Tornadoとは
http://www.tornadoweb.org/en/stable/#  

Tornadoの公式サイトによると、以下のように説明されています。  

> TornadoはFriendFeedで開発されたPythonのWebフレームワーク（非同期通信ライブラリ）です。
ノンブロッキングネットワークI / Oを使用することで、Tornadoは数万のオープン接続に拡張でき、ロングポーリング、WebSocket、および各ユーザーへの長時間の接続が必要なその他のアプリケーションに最適です。

## 特徴
Tornadoは「ノンブロッキングI/O」であるということが最大の特徴です。そのため、システムの規模を変更しやすく、同時に大量のリクエストがあったとしても対応することが可能です。ポーリングが実装されるシステムなどの開発に向いています。 公式サイト：http://www.tornadoweb.org/en/stable/ 学習のしやすさ：1 英語の参考書籍はありましたが、日本語のものは検索しても見つかりませんでした。


## 参考
* [python/tornadoでカスタムしたエラーページを使う](https://qiita.com/dplusplus/items/c19ea01d7343a244d76d)
* [勉強ノート：Tornado](https://qiita.com/ukaz/items/02df25294c155bb31f5e)
* [勉強ノート：Tornado その２](https://qiita.com/ukaz/items/baffabf378fb6f536de8)
* [PythonのTornadoで解説入れながらLoginしてみる](https://conta.hatenablog.com/entry/2012/05/31/222940)
* [python+tornadoでWEBアプリケーションを作成する](https://qiita.com/t-iguchi/items/dbcea2f6bdea68cd0b80)
