# 🚀 Social Media Campaign Performance Tracker – Power BI

Analyze Facebook & Instagram ad campaign performance with interactive Power BI dashboards.

## 📌 Project Highlights
✔️ **Platform**: Power BI Desktop  
✔️ **Goal**: Measure Campaign Effectiveness, Engagement, CTR, and ROI  
✔️ **Data Source**: Excel Dataset (Ad performance metrics)  
✔️ **Skills Applied**: Data Visualization, DAX, Marketing Analytics  


## 📂 Dataset Overview
| Column Name         | Description |
|---------------------|-------------|
| ad_id               | Unique ad identifier |
| campaign_id         | Campaign reference ID |
| fb_campaign_id      | Facebook campaign ID |
| age                 | Target audience age group |
| gender              | Target audience gender |
| impressions         | Total ad views |
| clicks              | Total ad clicks |
| spent               | Amount spent |
| total_conversion    | Total recorded conversions |
| approved_conversion | Approved conversions |

---

## 📈 Key Metrics
- **CTR (Click-Through Rate)**  
  ```DAX
  CTR (%) = DIVIDE(SUM('Table'[clicks]), SUM('Table'[impressions])) * 100
  ROI (%) = DIVIDE(SUM('Table'[Estimated Revenue]) - SUM('Table'[spent]), SUM('Table'[spent])) * 100

📊 Dashboard Features
KPI Cards – Impressions, Clicks, Conversions, CTR, Revenue
Demographic Insights – Age & gender analysis
Campaign-Level Breakdown – Spend vs Conversions
CTR & ROI Trends – Campaign performance over time
Interest Category Analysis – Clicks & conversions by interest
