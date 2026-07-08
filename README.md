# 老師專案管理 Web 版

這是一個純前端的本地資料網頁版課程專案管理系統，適合部署到 GitHub Pages。

## 重要提醒

- 網頁本身不內建任何私人資料。
- 請不要把 `teacher_progress_backup_*.json` 或任何工作備份檔上傳到 GitHub。
- 使用時請在網頁內自行匯入 JSON 備份；資料會保存於瀏覽器的 IndexedDB。
- 若清除瀏覽器資料，網頁內資料也會消失，請定期匯出 JSON 備份。

## 功能

- 營運首頁：本月目標、正式課程、候補課程、完成數。
- 課程專案：錄播／直播、正式／候補／下月準備、目前階段、已完成標籤。
- 工作月曆：滿版任務、篩選、批次完成、延後、等待、刪除、今日收尾。
- 檢查清單：Todo 分組、子項目、範本匯入／儲存。
- 留言板：手動記錄老師回覆與狀況，自動加上時間。
- 本地保存：IndexedDB 自動保存。
- 匯入匯出：支援 JSON 備份匯入與匯出。

## 本機測試

直接雙擊 `index.html` 開啟即可。

## GitHub Pages 部署

1. 建立或開啟 GitHub repository。
2. 上傳本資料夾內的檔案：`index.html`、`404.html`、`.nojekyll`、`.gitignore`。
3. 進入 repository 的 Settings → Pages。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，資料夾選擇 `/root`。
6. 儲存後等待 GitHub Pages 建置完成。

