# 社會心理學｜個人學習 Wiki

這是一個可直接部署到 **GitHub Pages** 的靜態網站資料夾，整合社會心理學第 1～7 章的學習索引與整理內容。

## 目前包含

- `index.html`：Wiki 首頁與章節瀏覽介面。
- `assets/style.css`：簡約、響應式樣式。
- `assets/app.js`：章節導覽與搜尋。
- `content/wiki-data.json`：網站使用的章節資料。
- `content/chapter-01.md`～`chapter-07.md`：各章 Markdown 文件。
- `content/chapter-07-terms.md`：第七章 21 個名詞概念卡。
- `content/chapter-07-essays.md`：第七章 7 題申論題訂正索引。
- `SOURCES.md`：來源與可信度標記規則。

## 上傳到 GitHub

1. 在 GitHub 建立一個新的 Repository。
2. 解壓縮本資料夾。
3. 將資料夾內的**所有檔案與子資料夾**上傳到 Repository 根目錄（不要只上傳 ZIP）。
4. 進入 Repository 的 **Settings → Pages**。
5. 在 Build and deployment 選擇 **Deploy from a branch**。
6. Branch 選 `main`，Folder 選 `/ (root)`，按 Save。
7. 等待 GitHub Pages 部署完成，便可使用頁面提供的網址。

## 本機預覽

可直接用瀏覽器開啟 `index.html`。若瀏覽器因本機安全限制無法載入 JSON，請使用 GitHub Pages 網址檢視；部署後網站會正常讀取資料。

## 內容完整度說明

這是**可部署的初始版**，不是已完成逐字匯入的最終知識庫。第 1～6 章目前先建立章節骨架與待補標記；第 7 章已放入 21 個名詞概念卡及 7 題申論題索引。概念數量只是目前初步統計，尚未完成跨章去重與正式核定。

後續更新時，請保留「原始題目／使用者原答／訂正答案／老師正式評分標準／AI 參考補充」的區分，缺漏一律標示「待補充」，不可自行新增成課程事實。
