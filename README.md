# 🍉 合成西瓜 (Suika Game) - 網頁版

這是一個基於 HTML5 Canvas 開發的合成西瓜遊戲，具備物理引擎優化與全球排行榜功能。

## 🚀 遊戲網址
[點我開始遊玩](https://sam20180811-cloud.github.io/suika-game/)

## 🎮 遊戲特色
* **物理引擎優化**：採用 Sub-stepping 技術，解決高速碰撞下的穿透問題。
* **進化導覽列**：頂部即時顯示水果合成順序。
* **全球排行榜**：自動記錄最高分，與全球玩家競爭。
* **行動裝置優化**：支援手機觸控操作。

## 📂 專案結構
* `index.html`: 遊戲主程式與 UI 介面。
* `code.gs`: 後端 API (部署於 Google Apps Script)，負責讀寫 Google Sheet 分數。

## 🔐 參觀帳號 (測試用)
如果你需要測試登入功能，可以使用以下資訊：
* **帳號**：`Guest`
* **密碼**：`1234`

## 🛠 使用技術
* Frontend: HTML5, CSS3, JavaScript (Canvas API)
* Backend: Google Apps Script (GAS)
* Database: Google Sheets
