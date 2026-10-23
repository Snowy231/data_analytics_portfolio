# Global Sales Business Intelligence Project (2003-2005)

## 📌 Project Overview
This project is an end-to-end data analytics and Business Intelligence exercise. It takes a raw sales dataset of 2,823 line items and transforms it into an interactive Excel dashboard. The goal was to answer two core business questions:
1. Where should the sales team focus efforts next quarter to grow revenue?
2. Where is revenue currently at risk?

## 🗂️ Repository Contents & Workflow
This repository is structured to show the complete data lifecycle, from raw data to final insights:

*   **01_Raw_Data:** The original, messy Kaggle dataset (CSV).
*   **02_Inspect_Report:** An initial data profiling document identifying missing values, duplicate risks, and data type issues.
*   **03_Data_Cleaning_Changelog:** A detailed Excel log of every transformation made in Power Query. It documents what was changed, why, and the result (e.g., investigating the Sales vs. Price anomaly, and excluding Pending orders from risk calculations).
*   **04_Analysis_Summary:** A written business report outlining the findings, limitations, and final recommendations.
*   **05_Final_Dashboard:** The complete interactive Excel workbook containing the raw data, cleaned data, PivotTables, charts, and the two final dashboard tabs.

## 💡 Key Business Insights & Recommendations

### 🟢 The Growth View (Revenue Expansion)
*   **The Core is Strong:** EMEA and NA drive 89% of revenue and are growing (+113% YoY).
*   **The APAC Opportunity:** APAC buys a fundamentally different product mix. While EMEA relies on Classic Cars (41% mix), APAC relies on Vintage Cars (39% mix) and Trucks (20%).
*   **Recommendation:** Protect and grow the EMEA/NA core, but pivot the APAC inventory, sales targets, and marketing to match their actual buying preferences. 

### 🟡 The Risk View (Order Health)
*   **Operational Health is High:** 94.5% of all orders completed without incident.
*   **Financial Exposure:** While only 11 orders were problematic (At Risk or Failed), they represent $445,679 in revenue exposure.
*   **Recommendation:** Focus account management attention on the specific territories and product lines driving these 11 problematic orders. (Note: Sample size is small, so per-territory risk rates should be interpreted with caution).

## 🛠️ Tools & Techniques Used
*   **Data Cleaning:** Power Query (removing PII, standardizing categories, handling nulls, creating diagnostic columns).
*   **Data Analysis:** Hypothesis testing (investigating a 45% variance anomaly between calculated revenue and recorded sales).
*   **Dashboard Design:** Excel PivotTables, PivotCharts, Slicers, and custom UI design (Color psychology: Green for Growth, Yellow for Risk).
