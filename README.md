# webemon games

ブラウザで遊べる自作ゲーム置き場。GitHub Pages で公開。

**https://webemon0101.github.io/games/**

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
