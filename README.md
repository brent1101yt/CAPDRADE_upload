# 📝 會考成績紀錄器 (CAP Score Tracker)

一個國中會考成績管理工具。提供直觀的介面，幫助考生記錄歷次模擬考成績、自動計算積分，並進行簡單的弱點分析。


## ✨ 特色功能

- **📊 自動積分計算**：輸入等級（A++、B+ 等）後，系統自動轉換為積分並加總。
- **🔍 弱點分析**：根據歷次紀錄自動計算各科平均值，提醒最需補強的科目。
- **💾 本地儲存**：資料儲存在瀏覽器的 `LocalStorage` 中，重新整理或關閉視窗資料也不會消失。
- **📥 Excel 匯出**：整合 **SheetJS** 函式庫，一鍵將所有紀錄匯出成 Excel 表格，方便備份與列印。
- **📱 響應式設計**：採用 Tailwind CSS，無論是手機或電腦都能完美顯示。

## 🚀 快速開始

1. **線上使用**：https://brent1101yt.github.io/CAPDRADE_upload/
2. **本地執行**：
   - 下載本專案的 `index.html`。
   - 直接用瀏覽器開啟即可使用，無需安裝任何伺服器環境。

## 🛠️ 使用技術

- **前端框架**：[Tailwind CSS](https://tailwindcss.com/) (UI 樣式)
- **核心邏輯**：原生 JavaScript (Vanilla JS)
- **Excel 處理**：[SheetJS (XLSX)](https://sheetjs.com/) (社群免費版)
- **圖示**：Lucide Icons / SVG

## 📁 資料安全與隱私

- 本程式為 **純前端運作**。
- 所有的成績資料僅儲存在您的個人電腦（瀏覽器）中，不會上傳至任何雲端伺服器，請放心使用。

## ⚖️ 授權聲明 (License)

本專案採用 **Apache License 2.0** 授權。
其中使用的第三方套件 **SheetJS (Community Edition)** 遵循其原有的開源授權條款。
