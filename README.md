# software-info

nekobata のソフトウェアの公開情報です。アプリの「更新の確認」がここのファイルを読みます。

| フォルダー | ソフトウェア | 内容 |
|---|---|---|
| `AIMosaicStudio/` | AI モザイクスタジオ | `update.json`: 最新のバージョン・日付・更新内容・ダウンロードページ（BOOTH） |

## update.json

```json
{
  "schema": 1,
  "product": "AIMosaicStudio",
  "name": "AI モザイクスタジオ",
  "version": "3.4.0",
  "date": "2026-11-08",
  "url": "https://nekomessy.booth.pm/items/9025512",
  "notes": "更新内容"
}
```

アプリは `https://raw.githubusercontent.com/nekobata/software-info/main/<製品>/update.json` を GET で読むだけです。
画像・動画・ファイル名・設定などは送りません。配布ファイルはここには置きません（BOOTH から入手してください）。