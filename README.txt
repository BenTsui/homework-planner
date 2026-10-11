每日作業進度表 PWA — iPad 使用方式

1. 將此資料夾內的所有檔案上傳到同一個 GitHub Repository。
2. GitHub Repository → Settings → Pages。
3. Build and deployment 選 Deploy from a branch。
4. Branch 選 main / root，按 Save。
5. 等 GitHub Pages 網址出現後，用 iPad 的 Safari 開啟。
6. Safari → 分享 → 加入主畫面。
7. 之後從 iPad 主畫面的「作業清單」圖示開啟即可。

預設家長 PIN：1234
第一次使用後，建議進入家長模式修改 PIN。

檔案：
- index.html：主程式
- manifest.webmanifest：PWA 設定
- sw.js：離線快取
- icon-192.png / icon-512.png：主畫面圖示

注意：
- 作業資料保存在該 iPad 的瀏覽器 localStorage。
- 若刪除 Safari 網站資料，紀錄也會被清除。
- 如果換另一台裝置，不會自動同步。
