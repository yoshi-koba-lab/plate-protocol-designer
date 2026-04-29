# Plate Protocol Designer

ブラウザ上で動作するインタラクティブなセル培養プレートプロトコル設計ツール。サーバー不要、単一HTMLファイルで完結。

## 特徴

- 6 / 12 / 24 / 48 / 96-well プレート対応
- 複数の条件軸（Drug, Concentration, Time など）を色分けで一括適用
- ワンクリックで選択Wellに条件を反映
- Well毎のメモ機能（テーブル表示、選択中Wellをハイライト）
- 行/列で共通する条件を自動判定して、ラベルとして外側に表示
- PDF / PNG 出力（画面表示と同じレイアウト）
- JSON 保存・読込（localStorage 自動保存付き）
- Undo / Redo（⌘Z / ⌘⇧Z）
- 凡例・メモパネルはドラッグで自由に配置可能

## 使い方

1. このリポジトリをダウンロード（または `index.html` だけでも可）
2. `index.html` をブラウザで開く

それだけです。サーバー不要、インストール不要。

### ローカルサーバー（任意）

File System Access API（保存/読込フォルダの記憶）をフルに使いたい場合は HTTP 経由で開いた方が確実です：

```bash
node server.js
# → http://localhost:8765
```

## ライセンス

MIT
