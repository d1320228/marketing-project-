# 🎥 乙七影展專題：Vibe Coding 與 AI 協作 Prompt 說明檔

本文件記錄了逢甲大學行銷學系大二專題《乙七影展》在網頁開發與企劃梳理過程中，運用 AI 協作與 **Vibe Coding** 的核心指令（Prompt）策略與架構。

---

## 1. 核心開發框架：RACES 提示詞框架
在本次專題開發中，我們採用了 **RACES 提示詞框架** 來引導 AI 進行精準的程式碼生成與內容結構化：

* **R (Role / 角色設定)**：設定 AI 扮演具備前端開發與行銷企劃專業的技術協作者。
* **A (Action / 具體行動)**：明確指示 AI 建立模組化 CSS（`base.css`、`layout.css`、`components.css`、`responsive.css`）以及單頁式 RWD 導覽架構。
* **C (Context / 專案背景)**：基於《乙七影展》完整企劃書，聚焦於台灣漫畫文化保存與國家漫畫博物館。
* **E (Execution / 執行細節)**：要求加入 Grid 網格系統、SEO Meta 標籤、YouTube 影片嵌入與手繪分鏡圖尺寸縮小。
* **S (State / 交付狀態)**：確保程式碼無外部雜訊與浮水印，並符合部署至 InfinityFree 與 Vercel 的標準。

---

## 2. 關鍵 Prompt 範例紀錄

### 💡 範例一：專案架構與 CSS 模組化指令
> **Prompt：**
> 「請協助建立逢甲大學行銷學系大二專題《乙七影展》的網頁架構。需採用單頁式結構並透過錨點跳轉，同時將 CSS 檔案切割為 base.css、layout.css、components.css 與 responsive.css 四個檔案放入 css/ 資料夾中，並具備完整 RWD 與 Grid System。」

### 💡 範例二：內容對齊與圖片格式指令
> **Prompt：**
> 「所有網頁內容必須完全基於專題企劃書，移除所有外部參考浮水印；手繪分鏡圖副檔名需對應大寫的 `.PNG` 格式並適度縮小尺寸，頁尾製作日期設為 2026年11月5日。」

---
