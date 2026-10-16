# 多益三日衝刺

多益練習 App，可以加到 iPhone 主畫面，像一般 App 一樣開啟，沒網路也能用。

## 安裝到 iPhone

1. 用 **Safari** 打開 https://yilan21.github.io/toeic-app/
2. 按下方的「分享」按鈕，選「加入主畫面」。
3. 之後從主畫面的 TOEIC 圖示打開。

## 進度

進度存在手機裡（localStorage），沒有雲端備份。首頁最下面的「備份與搬移進度」可以複製備份碼，或下載備份檔，再到另一個版本匯入。

## 檔案

- `index.html`：整個 App（單一檔案）
- `manifest.webmanifest`、`icons/`：主畫面名稱與圖示
- `sw.js`：離線快取。改版時把裡面的 `VERSION` 加 1。
