# Casetify Keyword Bidding Strategy | Casetify 關鍵字廣告競價策略

A quantitative optimization project using Management Science techniques to determine the most cost-effective Google Ads bidding strategy for Casetify, maximizing total clicks under a fixed budget.

針對 Casetify 關鍵字廣告制定最佳競價策略，在固定預算限制下，最大化廣告總點擊數並優化成本效益。

> **國立政治大學 管理科學課程 · NCCU Management Science Final Project · 2023 · 第九組**

---

## 🎯 Objective | 分析目標
Optimize Google Ads keyword bidding by determining the best budget level and rank for 5 core keywords (e.g., iPhone13, custom cases), aiming to maximize overall traffic while staying within a $10,000 budget.

優化 Google Ads 關鍵字競價策略：針對五個核心關鍵字（如：iPhone13、客製化等）決定最佳預算等級與排名，目標在 10,000 元預算限制下實現點擊數最大化。

---

## 🛠 Pipeline | 處理流程
1. **Keyword Research:** Selecting 5 high-relevance keywords via Google Ads Keyword Planner. / 透過 Google Ads 關鍵字規劃工具篩選 5 個高關聯性關鍵字。
2. **Data Collection:** Gathering Monthly Search Volume, Competition, and Top-of-page bid ranges (Low/High). / 收集每月搜尋量、競爭程度及首頁頂端出價範圍（高價/低價區）。
3. **Estimation Modeling:** Calculating CTR and CPC for 5 different budget levels and 5 ranks per keyword. / 針對每個關鍵字計算 5 種預算等級與 5 種排名下的點擊率 (CTR) 與單次點擊成本 (CPC)。
4. **Optimization Modeling:** Defining decision variables, objective functions (Max Clicks), and constraints (Budget <= 10,000). / 建立最佳化模型，定義決策變數、目標函數（最大點擊數）與限制條件（預算限制）。
5. **Sensitivity Analysis:** Evaluating the impact of budget changes on total clicks. / 進行敏感度分析，評估預算變動對總點擊數的影響。

---

## 💻 Tech Stack | 技術棧
* **Optimization Tool:** Solver (Excel/Google Sheets) / 線性規劃求解器
* **Research Tool:** Google Ads Keyword Planner / 關鍵字規劃工具
* **Data Science:** Quantitative Modeling & Sensitivity Analysis / 定量建模與敏感度分析

---

## 🧠 Optimization Logic | 最佳化邏輯
* **Decision Variables:** Choosing the optimal Budget Level (1-5) and Rank for each keyword. / 為每個關鍵字選擇最佳的預算等級與排名。
* **Constraints:** Total advertising spend must be lower than the predefined budget (e.g., 10,000). / 總廣告預算需低於設定上限。
* **Scenario Testing:** Testing performance across different budget thresholds (7,000 to 11,000). / 測試不同預算門檻（7,000 至 11,000）下的表現。

---

## 📊 Key Findings | 核心洞察
* **Optimal Allocation:** Under a $10,000 budget, the model achieved a maximum of **4,566 clicks**. / 在預算 10,000 元下，模型達成最大點擊數 4,566 次。
* **Keyword Strategy:** "iPhone13" performed best at Budget Level 2/Rank 3, while "Customization" and "Case" keywords were optimized at higher budget levels to capture volume. / 「iPhone13」在預算等級 2、排名 3 表現最優；而「客製化」與「手機殼」則需配置較高預算等級以獲取流量。
* **Budget Elasticity:** Sensitivity analysis showed diminishing returns as budget increased beyond 10,000, identifying the "sweet spot" for ad spending. / 敏感度分析顯示預算超過 10,000 後邊際效益遞減，藉此找出最佳投放甜蜜點。

---

## 👥 Team Members | 團隊成員
* **黃筠茜 (Athena Huang):** Quantitative Modeling & Optimization / 模型建立與最佳化
* **楊鵑慈:** Result Analysis / 結果分析
* **花巧臻:** Data Collection / 資料收集
* **黃任謙:** Data Preprocessing / 資料處理
* **黃慧如:** Market Research / 市場研究
* **劉家妤:** Market Research / 市場研究

---

## 中文簡介
本專案為政大管理科學課程之期末專案。透過 Google Ads 關鍵字規劃工具提取 Casetify 相關熱門詞彙（如 iPhone13、手機背帶等），並運用線性規劃（Linear Programming）建立競價最佳化模型。在給定的預算約束下，計算不同出價排名對點擊率（CTR）與成本（CPC）的影響，最終求得最大化點擊數的配置組合，並進行預算敏感度分析以提供投放策略建議。
