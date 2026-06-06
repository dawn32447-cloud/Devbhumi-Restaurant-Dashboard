Devbhumi Delicacies Restaurant Performance & Economics Analytics

## 📊 Project Overview
This project features a 2-page, high-contrast executive Power BI dashboard built to analyze sales velocity, unit economics, and supply chain/operational turnaround times for a multi-location restaurant brand. 

*Note: Proprietary business data has been fully anonymized, transformed, and scaled with explicit permission from the stakeholder to preserve confidentiality.*

---

## 🛠️ Key Analytical Features Built
*   Star-Schema Data Modeling: Transformed flat transaction data into structured operational matrices.
*   Advanced DAX Calculations: Developed time-intelligence trends (MoM Growth), dynamic financial margins, and localized logistics metrics.
*   User-Centric UI/UX: Built an immersive dark-mode grid layout with focused callout KPI thresholds to quickly highlight performance exceptions.

---

## 📈 Dashboard Insights & Visualizations

### 1. Financial & Sales Strategy Page
This view tracks high-level corporate health, platform order shares, and monthly profitability margins.
<img width="1345" height="750" alt="Screenshot 2026-06-03 195707" src="https://github.com/user-attachments/assets/e9dc288f-0fd8-45e9-b326-cfc4a3eaddc6" />


*   Key Insight Discovered: "While total order volume spiked by 12K, high commission leakages on third-party food delivery platforms squeezed net profit margins down to 16%."

### 2. Operational Efficiency & Logistics Page
This view tracks kitchen fulfillment velocity vs. customer ratings to flag quality bottlenecks.
<img width="1346" height="738" alt="Screenshot 2026-06-03 195726" src="https://github.com/user-attachments/assets/b49b522f-0b37-4bc7-99bd-6b487956fcae" />


*   Key Insight Discovered: "The Food Truck segment maintained the highest customer satisfaction (3.01 average rating) despite having a combined 47.42-minute turnaround cycle, pinpointing strong brand loyalty."

---

## 🧠 Sample DAX Measures Showcased

```dax
Total Net Profit = SUM('Table1'[Net_Profit])
