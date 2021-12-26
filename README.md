# vcchecker 高速ワクチン接種証明書チェッカー

[新型コロナワクチン接種証明書アプリ](https://www.digital.go.jp/policies/posts/vaccinecert)で生成された証明書を[jsQR-es](https://github.com/code4fukui/jsQR-es)でQRコードを読み取り、[SMARTHealthCard-es](https://github.com/code4fukui/SMARTHealthCard-es)でデコードと[デジタル庁の公開鍵](https://vc.vrs.digital.go.jp/issuer/.well-known/jwks.json)を使って検証を行いAR表示するWebアプリです。

- [高速ワクチン接種証明書チェッカー](https://code4fukui.github.io/vcchecker/)

<img width="354" alt="vcchecker-nomargin" src="https://user-images.githubusercontent.com/1715217/147420803-64ab2df0-d77c-494f-9db4-e20d10c7b79d.png">
