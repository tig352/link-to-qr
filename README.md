# Link to QR Code

一個免費、免註冊的網址轉 QR Code 網頁。輸入網址即可生成 QR Code，並下載 PNG 或複製網址。

## 網站特色

- QR Code 在瀏覽器本機生成，不會把網址送到第三方服務。
- 支援 HTTP 與 HTTPS 網址，省略協定時會自動補上 HTTPS。
- 適配手機與桌面瀏覽器。
- 網頁為純 HTML、CSS、JavaScript，無需安裝依賴或建置。

## 部署到 GitHub Pages

Repository 已附上 GitHub Actions workflow：推送到 main 分支後會自動部署。

1. 到 repository 的 Settings → Pages，將 Build and deployment 設為 GitHub Actions。
2. 等待 Actions 頁面的 Deploy to GitHub Pages 工作完成。
3. 網站網址會是 https://tig352.github.io/link-to-qr/ 。

## 本機預覽

直接用瀏覽器開啟 index.html 即可。
