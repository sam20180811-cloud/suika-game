# 🍉 合成西瓜遊戲專案報告

## 3.1 專案資訊
* **網站網址**：[https://sam20180811-cloud.github.io/suika-game/](https://sam20180811-cloud.github.io/suika-game/)
* **可使用的參觀帳號**：`Guest`
* **可使用的參觀密碼**：`1234`

---

## 3.2 前端網站架構說明
本專案之前端架構部署於 GitHub Pages，主要由兩個獨立的 HTML 檔案組成，分別負責遊戲主體與數據呈現。

### 📂 檔案結構與目的說明
1. **`index.html` (遊戲主程式)**
   - **目的**：作為網站首頁與遊戲核心。負責繪製 Canvas 畫布、處理物理引擎碰撞、捕捉觸控/滑鼠事件。
   - **核心功能**：即時計算分數、顯示水果進化序列，並透過 Fetch API 與後端 Google Apps Script 溝通。

2. **`leaderboard.html` (獨立排行榜頁)**
   - **目的**：提供完整的數據展示介面。
   - **核心功能**：獨立讀取資料庫（Google Sheets）中的歷史最高分紀錄，並以視覺化表格呈現全球前十名玩家。

### 🖼 前端網站檔案結構截圖
*(建議此處上傳一張您 GitHub 檔案列表的截圖，畫面中需同時看到 index.html 與 leaderboard.html)*

---

## 🛠 技術棧說明
* **前端**：HTML5 Canvas, CSS3 Flexbox/Grid, Vanilla JavaScript.
* **後端**：Google Apps Script (GAS) 作為 API 伺服器。
* **資料庫**：Google Sheets (試算表) 進行資料持久化存儲。
