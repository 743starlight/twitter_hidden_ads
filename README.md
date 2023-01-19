# PC版twitter.comから広告・トレンドなど余計な表示を消すuser css

## 対応する環境
- Google ChromeやChrome拡張を使えるブラウザ
- ↑に加えてUser CSSなどユーザーCSSが使えるプラグイン。

https://chrome.google.com/webstore/detail/user-css/okpjlejfhacmgjkmknjhadmkdbcldfcb

オンオフし易いし・インターフェースがわかりやすい。

## User CSSでの設定方法
- 上記リンクからUser CSSをインストール
- http://twitter.com/home にジャンプ
- 右上のUser CSSのアイコン[CSS]←こんなやつ をクリック
- [common.css]の内容をコピペ

https://github.com/743starlight/twitter_hidden_ads/blob/main/common.css

## ポイント
- 最右部の表示は丸々消すコードになってます。
- twitter.comの仕様変更などで使えなくなる、またはもしくは表示がおかしくなるかも。変だと思うことがあったら「ON□」トグルボタンを押すとオンオフできます。
- 700px、430pxの部分を調整すると画面幅を調節できます。
- 殴り書きなんで、もっといいCSSがあったら教えてください。



