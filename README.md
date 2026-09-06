# HAMZWORKERZ games

ブラウザで遊べる自作ゲーム置き場。GitHub Pages で公開（リポジトリ名 `webemon0101.github.io`）。

**https://webemon0101.github.io/**

| ゲーム | フォルダ | 内容 |
|---|---|---|
| AETHER WARDEN | [`aether-warden/`](aether-warden/) | 縦スクロール・スペースシューター |
| FIRE RESCUE | [`fire/`](fire/) | ゲーム＆ウオッチ風レトロLCDゲーム |

## 構成

- ルートの `index.html` … ゲーム選択メニュー
- 各ゲームは `<フォルダ名>/index.html` の単一 HTML ファイル（外部ライブラリなし）

## 新しいゲームを追加する

1. `新フォルダ/index.html` を作る
2. ルートの `index.html` のメニューにカードを1枚追加する
3. `main` へ commit & push（数十秒で Pages に反映）

## 広告 (Google AdSense)

- 各ページの `<head>` にローダー、ルートに `ads.txt`（`https://webemon0101.github.io/ads.txt`）。
- メニュー `index.html` に手動ディスプレイ枠あり。AdSense で作成した10桁のスロットIDを
  `data-ad-slot="0000000000"` と差し替えると有効化。未配信の間は自動で非表示。
