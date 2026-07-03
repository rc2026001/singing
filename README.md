# 歌唱練習室

跟著 YouTube 練唱的網頁小工具:即時音準、音量、穩定度與持續音偵測,A-B 反覆練習、變速播放、歌詞與筆記、練習紀錄與自動回饋。所有個人資料只儲存在使用者自己的裝置上(localStorage),不需要帳號、沒有伺服器。

## 檔案清單

| 檔案 | 用途 |
|---|---|
| `index.html` | 整個應用程式(必要) |
| `manifest.json` | 讓網站可以安裝成手機App(PWA) |
| `sw.js` | Service worker,支援App安裝與離線開啟外殼 |
| `icon-192.png` / `icon-512.png` | App圖示 |

## 發佈到 GitHub Pages(免費)

1. 到 github.com 註冊/登入(免費帳號即可)
2. 右上 **+** → **New repository**,取個名字(例如 `singing-practice`),保持 **Public**,按 **Create repository**
3. **Add file → Upload files**,把這 5 個檔案全部拖進去,按 **Commit changes**
4. 到 repo 的 **Settings → Pages**,Branch 選 `main` 與 `/ (root)`,按 **Save**
5. 等約一分鐘後重新整理,就會看到你的網址,例如:
   `https://你的帳號.github.io/singing-practice/`

之後要更新,只要重新上傳覆蓋 `index.html` 即可。

## 給使用者的提醒

- **請戴耳機使用**,麥克風才不會把伴奏一起收進去
- 需要 HTTPS 才能使用麥克風(GitHub Pages 預設就是 HTTPS)
- iPhone:Safari 分享 → 加入主畫面;Android:Chrome 選單 → 安裝應用程式
