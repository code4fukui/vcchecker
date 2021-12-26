# vcchecker 高速ワクチン接種証明書チェッカー

[新型コロナワクチン接種証明書アプリ](https://www.digital.go.jp/policies/posts/vaccinecert)で生成された証明書を[jsQR-es](https://github.com/code4fukui/jsQR-es)でQRコードを読み取り、[SMARTHealthCard-es](https://github.com/code4fukui/SMARTHealthCard-es)でデコードと[デジタル庁の公開鍵](https://vc.vrs.digital.go.jp/issuer/.well-known/jwks.json)を使って検証を行いAR表示するWebアプリです。

- [高速ワクチン接種証明書チェッカー](https://code4fukui.github.io/vcchecker/)

<img width="610" alt="vcchecker" src="https://user-images.githubusercontent.com/1715217/147420791-4fc126d7-f224-4830-81c7-0d01720d709d.png">
