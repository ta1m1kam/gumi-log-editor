# グミログ

グミレビューの Instagram 投稿文を、スマホからステップ入力で作るツール。PWA 対応。

- `index.html` : アプリ本体（ビルド不要の単一ファイル）
- `sw.js` / `manifest.webmanifest` : PWA 用
- `icons/` : アプリアイコン（`icon.svg` から `rsvg-convert` で生成）

ローカル確認: `python3 -m http.server 8765` して `http://localhost:8765/` を開く。
