# shared-horses-data

共通馬データの正本リポジトリです。

- データ: `horses.json`
- 管理画面: `index.html`

## 管理画面でできること

- 全項目の一覧表示
- セル編集
- 行の追加 / 削除
- 項目（列）の追加
- `horses.json` エクスポート

## 使い方

1. `index.html` を開く（Pages かローカルHTTPサーバー）
2. 画面で編集する
3. `JSONエクスポート` で `horses.json` を保存
4. リポジトリ内の `horses.json` を置き換えて commit / push

ローカルで確認する場合:

```bash
cd /Users/gue1971/MyWorks/競馬/出資馬アプリ/shared-horses-data
python3 -m http.server 8080
```

`http://localhost:8080/` を開きます。
