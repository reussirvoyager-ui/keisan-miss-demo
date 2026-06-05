# 計算ミス ノート（デモ版）

医学部専門予備校レユシールのHP掲載用デモ。渋谷さん版（keisan-miss-shibuya）のUI構成を踏襲し、データを架空の生徒のサンプル12件（NotionデモDB「🧮 計算ミスアプリ（デモ）」と同一）に差し替えたもの。

- 単一ファイル（index.html）・依存なし・APIトークンなし
- 新規記録・解決チェックは localStorage（端末内）のみに保存
- デザイン: レユシール3色規律（紺 #1B2A4A／クリーム #F7F5F0／金 #BF9B56）

## 公開手順（GitHub Pages）

```bash
# reussirvoyager-ui アカウントで新規リポジトリ keisan-miss-demo を作成してから:
cd keisan-miss-demo
git init
git add .
git commit -m "計算ミスノート デモ版"
git branch -M main
git remote add origin https://github.com/reussirvoyager-ui/keisan-miss-demo.git
git push -u origin main
# GitHub → Settings → Pages → Branch: main / (root) → Save
```

公開URL: https://reussirvoyager-ui.github.io/keisan-miss-demo/
（Notionデモページの「計算ミス記録アプリ（デモ版）」リンクはこのURLに設定済み）
