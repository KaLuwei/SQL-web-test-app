[github_readme.md](https://github.com/user-attachments/files/34469331/github_readme.md)
# 📊 SQL 互動查詢學習工作站 (SQL Studio)

一個建構於瀏覽器端的純前端互動式 SQL 學習與查詢平台。內建 SQLite WebAssembly 引擎、ERD 關聯圖顯示、數據視覺化與語法排錯助手。

線上體驗網址：[https://KaLuwei.github.io/sql-studio/](https://KaLuwei.github.io/sql-studio/)

---

## 🌟 核心特色

1. **⚡ 純瀏覽器端 SQLite 引擎**：採用 `sql.js (WebAssembly)`，無需安裝任何伺服器或資料庫即可立即執行 SQL。
2. **🗺️ 視覺化 ERD 關聯圖**：標準 Crow's Foot / Flow 佈局，清楚展示主鍵 (PK) 與外鍵 (FK) 對應關係。
3. **📊 數據視覺化 Chart.js**：查詢結果可一鍵切換為動態圖表 (Bar Chart)。
4. **💡 智能語法助手 (Smart Linter)**：針對 `WHERE` 誤用聚合函數、遺漏 `GROUP BY` 或資料表名稱寫錯提供修改建議。
5. **🗃️ 多主題資料集與 CSV 上傳**：
   * 內建 3C 電商、SaaS 訂閱制、美食外送 3 套主題資料庫。
   * 支援上傳自訂 `.csv` 檔案並自動建立 Table。
6. **💾 完整 DDL / DML 備份導出**：可將目前編輯後的資料庫結構與數據導出為標準 `.sql` 檔。

---

## 🚀 本地開發與部署 (Local Setup)

本專案為單一 HTML 檔案 (`index.html`)，無需安裝 `node_modules` 或建置步驟：

```bash
# 複製專案
git clone https://github.com/KaLuwei/sql-studio.git

# 直接使用瀏覽器開啟 index.html 即可運行
```

---

## 📄 授權條款

MIT License
