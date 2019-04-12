# PWA

さっくりと調べてみました。  

## PWAとはなにか

- iTuensStoreやGooglePlayを経由することなくアプリがインストールできる

- プッシュ通知などにも対応している

- オフラインでも動作する

- デスクトップ版もある

下記のサイトがわかりやすい  
[PWAがもたらすこれからのwebの姿](https://mya-ake.com/slides/pwa-will-provide-future-web)  

[PWA Progressive Web Apps とは？ネイティブアプリ開発との違い](https://yapp.li/magazine/2292/)  

## PWAが利用されている企業

一覧  
[PWAは世界中で広まっている](https://mya-ake.com/slides/pwa-will-provide-future-web#26)  

有名所だと  

[suumo](https://suumo.jp/hokkaido/)  

[starbucks](https://app.starbucks.com/)  

[日経新聞](https://r.nikkei.com/)  

## デスクトップ版PWA

デスクトップ版もある。  

- Chromeを起動

- アドレスバーに[chrome://flags]と打ち込む

- 検索窓に[PWA]を入力

- 下記のフラグを"Enabled"に変更する

  - Desktop PWAs
  - Desktop PWAs Link Capturing
  - Desktop PWAs Custom Tab UI
  - Desktop PWAs out-of-scope links open in the app window
  - System Web Apps

- 再起動する

- starbucksのサイトへ移動  
[starbucks](https://app.starbucks.com/)  

- Chrome右上の設定項目をクリック

- 「starbucksをインストール」をクリック

- popupで"インストール"を選択  


## 開発方法

めっちゃ簡単。  

[PWAをもっと簡単に初めてみる](https://qiita.com/poster-keisuke/items/6651140fa20c7aa18474)  

## メリット

- OS毎の開発がいらない

- Storeへの申請が不要

- 既存のサイトがあれば開発が簡単

- ブラウザ依存のため、検証の手間暇がサイトと変わらない？(予想)

- ServiceWorkerを利用すれば高速化も可能?(予想)

- ブラウザバックが防げる

## デメリット

- 完全にネイティヴアプリと同等にはできない  
　　→逆に言えば、サイトをアプリ化するだけならこのデメリットは考えなくてよい  

- 新しい技術で、まだユーザーへの認知度がそこまで高くない

- 画面遷移を考えないとユーザーが行き詰まる可能性がある(ブラウザバック非対応にした場合)

## 考慮点

- オフライン時の動作を考える必要あり(特に認証周り)

- 新しい技術で、まだ不明点も多い(本格的に調査すればある程度は明確にできる)

[公式サイト](https://developers.google.com/web/progressive-web-apps/?hl=ja)  

## スマホの現状

- ユーザーの利用率は アプリ:85% Web:15%(2017年度)  
[スマートフォンでは平均30個のアプリが利用され、利用時間の85%を占める](https://www.netratings.co.jp/news_release/2017/11/Newsrelease20171108.html)  

- アプリ対応したほうが利用率が増えるかも？
