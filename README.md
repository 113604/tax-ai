# Tax AI（Smart Tax Assistant）

## 使用方式
1. 直接雙擊 `index.html` 即可離線使用。
2. 若部署到 GitHub Pages 或任何網站空間，系統會自動讀取 `questionBank.json`。
3. 題庫更新時，請維持 JSON 欄位：`id`、`category`、`question`、`summary`、`answer`、`keywords`、`relatedIds`、`version`。

## 檔案
- index.html：網站頁面
- style.css：Fluent Design 視覺樣式
- app.js：介面、收藏、題庫瀏覽、詳情抽屜
- search.js：自然語言關鍵字、同義詞及排序引擎
- questionBank.json：109 題題庫資料

> 正式上線前，請由業務單位再次核對每題標準答詢。
