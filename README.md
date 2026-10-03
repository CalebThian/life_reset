# Life Reset 管家

深色 RPG 風格的每日習慣養成 PWA，繁體中文，資料存於手機瀏覽器（localStorage）。

## 檔案
- `index.html` — 全部程式（HTML/CSS/JS 單檔）
- `manifest.json`、`sw.js`、`icon-*.png` — PWA 安裝與離線支援

## 在電腦上試用
直接用瀏覽器開啟 `index.html` 即可（離線快取功能需透過 https 或 localhost 才會啟用）。

## 安裝到 iPhone（免費，約 5 分鐘）
1. 到 GitHub 建立一個新的 repo（例如 `life_reset`），把這個資料夾的檔案全部上傳。
2. Repo → Settings → Pages → Source 選 `main` 分支、根目錄 `/`，儲存。
3. 等 1 分鐘後會得到網址 `https://<你的帳號>.github.io/life_reset/`。
4. 用 iPhone **Safari** 開啟該網址 → 點「分享」→「加入主畫面」。
5. 之後從主畫面開啟就是全螢幕 App，離線也能用。

## 更新程式
修改 `index.html` 後重新上傳，手機上重新整理一次即可（`sw.js` 採網路優先策略）。
若改了快取清單，記得把 `sw.js` 內的 `CACHE` 版本號 +1。

## 備份
「設定」頁可匯出 / 匯入 JSON 備份；換手機或清除瀏覽器資料前請先匯出。
