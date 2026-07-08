# GitHub Pages 上傳教學

## 方式一：用 GitHub 網頁上傳

1. 打開你的 GitHub repository。
2. 點 `Add file` → `Upload files`。
3. 把這個資料夾中的檔案拖進去：
   - index.html
   - 404.html
   - .nojekyll
   - .gitignore
   - README.md
4. 點 `Commit changes`。
5. 到 `Settings` → `Pages`。
6. Source 選 `Deploy from a branch`。
7. Branch 選 `main`，資料夾選 `/root`。
8. 等 1～3 分鐘後，GitHub 會提供網址。

## 方式二：用終端機上傳

```bash
git clone https://github.com/<你的帳號>/<你的repo>.git
cd <你的repo>
cp -R /你的下載位置/teacher_project_manager_web_github_ready/* .
git add .
git commit -m "Add teacher project manager web app"
git push
```

## 不要上傳的檔案

請不要把任何含有老師資料的 JSON 備份放進 GitHub repository，例如：

```text
teacher_progress_backup_20260626.json
project_backup.json
*.zip 備份資料
```

本系統是讓你在網頁打開後自行上傳資料，資料只存在你的瀏覽器裡。
