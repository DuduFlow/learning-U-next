# 成交Ｕ之後｜GitHub Pages 完整版

08/25｜洪敬忠 分處經理

## 檔案

- index.html：課程首頁，五訪地圖、六個對話演練、五段導讀、測驗及下一訪計畫。
- style.css、main.js：全部課程樣式與互動程式。
- catalog/：原課程目錄的更新副本，08/25 已改為「成交Ｕ之後」並連到本包首頁，其他課程仍連到原線上頁面。
- .nojekyll：讓 GitHub Pages 直接提供靜態檔案。

## 上傳與發布

1. 解壓縮 ZIP，進入「成交U之後-GitHub完整版」資料夾。
2. 把資料夾內的所有檔案與 catalog 資料夾上傳到 GitHub repository 根目錄；根目錄應直接看到 index.html，不要再包一層資料夾。
3. 在 repository 的 Settings → Pages，選擇 Deploy from a branch，指定 main 分支與 / (root)，儲存。
4. 發布後，課程首頁為 https://你的帳號.github.io/你的repo名稱/；目錄為同一網址後加 catalog/。

如果要接回現有 learning_notes_catalog 網站：將本包 catalog/js/main.js 的第 11 堂 url 改為新課程實際網址，再替換原目錄的 js/main.js。不要把相對路徑 ../index.html 原樣搬到另一個 repository。

本課程頁不需 npm、建置工具或外部 CDN。閱讀勾選與筆記儲存在使用者瀏覽器，換裝置或網址不會自動同步。課程內數字與個案為逐字稿示例，不是保證結果。

已檢查 JavaScript 語法、章節連結、本地檔案與 ZIP 完整性。尚未完成實際瀏覽器畫面、點擊或 GitHub 線上驗證。
