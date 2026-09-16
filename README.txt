羽球人 PWA 測試版

部署到 GitHub Pages：
1. 將這個資料夾內的 index.html、manifest.webmanifest、sw.js、icons/ 上傳到你的 GitHub Pages repository。
2. 確認 GitHub Pages 使用 HTTPS。
3. iPhone 用 Safari 開啟網址。
4. 分享 → 加入主畫面。
5. 之後就會像 App 一樣從主畫面開啟。

注意：
- Service Worker 不會快取 Supabase API，避免舊資料被離線快取。
- 目前 Google OAuth 的 SITE_URL 仍沿用原本 GitHub Pages 網址。
- 手機版把左側選單改成底部導覽列。
