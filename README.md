# 學生個性決策樹測驗（GitHub Pages 版本）

這個資料夾包含可直接部署到 GitHub Pages 的靜態網站：

- `index.html`（已正確連結 `style.css` 與 `script.js`，並透過 CDN 載入 Chart.js）
- `style.css`
- `script.js`
- `.nojekyll`（避免 GitHub Pages 的 Jekyll 解析影響靜態資源）

## 部署步驟（GitHub Pages）

1. 登入 GitHub，建立新 Repository（例如：`personality-quiz`）。
2. **把本資料夾的所有檔案** 上傳到該 Repository 的 `main` 分支根目錄。
3. 進入 `Settings` → `Pages`：
   - **Source**：選 `Deploy from a branch`
   - **Branch**：選 `main`、資料夾 `/(root)`，儲存。
4. 等待 GitHub Pages 建置完成後，頁面會顯示公開網址（例如 `https://<你的帳號>.github.io/personality-quiz/`）。

## 在 Notion 嵌入
在 Notion 頁面輸入 `/embed`，貼上 GitHub Pages 的網址，即可在 Notion 內互動作答。

> 若需自訂子路徑或多頁面，請確保所有相對路徑（CSS/JS）保持為相對根目錄即可（本範例已配置為相對路徑）。
