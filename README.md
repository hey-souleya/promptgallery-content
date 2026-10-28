# 提示詞圖鑑 內容庫

App 打開時會到這裡抓最新內容。改這裡不用重新送審。

- `catalog.json`：所有風格（styles）和節慶特輯（events）
- `images/`：範例圖，檔名 `{id}_before.jpg`、`{id}_after.jpg`

## 加一個節慶特輯
在 `events` 加一筆：
```json
{"id":"xmas-2026","name":"聖誕節特輯","nameEn":"Christmas Special","emoji":"🎄",
 "from":"2026-12-18","to":"2026-12-26","styleIDs":["x01","x02","x03","x04","x05"]}
```
特輯的款式放在 `styles` 裡，`cat` 填 `"event"`，平常不會出現在分類裡，只在 from～to 期間的特輯裡看得到。
