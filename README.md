# 海野手帖 PWA

將這個資料夾的內容部署到任何靜態網站服務後，以 HTTPS 網址在手機開啟：

- iPhone Safari：分享 → 加入主畫面。
- Samsung Internet / Chrome：選單 → 加入主畫面或安裝應用程式。

真實地圖使用 OpenStreetMap 圖磚，站點與每一天的 Google 導航連結皆可直接開啟。首次載入後，核心頁面檔案會由 Service Worker 快取；地圖圖磚與外部字型仍需要網路。
