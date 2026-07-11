# Learning-KiCad-Projects
你好！我是 柯宇鴻，這是用來記錄我從零開始學習 KiCad PCB 設計的 GitHub 倉庫。
我希望藉由實作不同的專案，掌握電路圖設計與 PCB 佈線的技能，為未來的專案打下基礎。

## 🎯 KiCad 硬體開發標準 SOP 學習目標✅

為了掌握系統化的硬體電路設計流程，我將依據標準 SOP 逐步完成以下階段的學習與實作：

### 1. 原理圖設計 (Schematic Capture) 
- ⬜ 掌握元件庫搜尋與基本元件放置（R, C, IC, Connector）
- ⬜ 建立正確的網路標籤 (Net Label) 與電源/接地符號（VCC, GND）
- ⬜ 理解並正確放置「電源標籤」(Power Flag) 解決電源供應端判定問題
- ⬜ 執行原理圖「電氣規則檢查」(ERC) 並修正所有 Errors 與 Warnings

### 2. 元件庫管理與自建元件 (Library Management)
- ⬜ 學會閱讀晶片數據手冊 (Datasheet)，理解引腳定義與電氣屬性
- ⬜ 實作「自建電路圖符號」(Custom Symbol)，手動繪製晶片符號並設定 Pin Type (Input/Output/Power)
- ⬜ 實作「自建封裝」(Custom Footprint)，根據 Datasheet 尺寸精密計算焊盤 (Pad) 大小、間距 (Pitch) 與邊界線 (Courtyard)

### 3. 電路板佈線 (PCB Layout)
- ⬜ 將原理圖設計正確導入 PCB 編輯器中
- ⬜ 在 `Edge.Cuts` 層定義精確的電路板尺寸與板框
- ⬜ 設定符合生產工廠規範的「設計規則」(Constraints / Design Rules)，如線寬 (Track Width) 與安全間距 (Clearance)
- ⬜ 實作去耦電容 (Decoupling Capacitor)「盡量靠近晶片電源腳」的佈局規範
- ⬜ 實作大面積 GND 鋪銅 (Copper Pour / Zone) 與設定熱焊盤 (Thermal Relief)
- ⬜ 執行「設計規則檢查」(DRC) 確保板子無任何短路、斷路或間距衝突

### 4. 生產製造輸出 (Manufacturing & DFM)
- ⬜ 導出符合工廠打樣標準的 Gerber 光繪檔與鑽孔檔 (Drill files)
- ⬜ 使用 Gerber 查看器 (Gerber Viewer) 進行出廠前自主檢查
- ⬜ 輸出完整的物料清單 (BOM 表)
