# Commercial Store Sales Analysis

### Brief One‑Line Summary
Analyzing retail store sales data to extract insights into inventory performance and profitability using SQL, Python, and Power BI.

---

## Table of Contents
1. [Overview](#overview)  
2. [Business Problem](#business-problem)  
3. [Dataset](#dataset)  
4. [Tools and Technologies](#tools-and-technologies)  
5. [Project Structure](#project-structure)  
6. [Data Cleaning & Preparation](#data-cleaning--preparation)  
7. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
8. [Research Questions & Key Findings](#research-questions--key-findings)  
9. [Dashboard/Model/Output](#dashboardmodeloutput)  
10. [How to Run This Project?](#how-to-run-this-project)  
11. [Results & Conclusion](#results--conclusion)  
12. [Future Work](#future-work)  
13. [Author & Contact](#author--contact)

---

## Overview
This project investigates sales trends in commercial stores, focusing on understanding inventory performance, sales channel effectiveness, and product-category insights to support strategic business decisions.

---

## Business Problem
Retail stores often deal with excess inventory and missed revenue due to lack of actionable insights. How do we:
- Identify underperforming categories?
- Optimize inventory levels?
- Improve profitability and reduce waste?

---

## Dataset
- Source: `data/` folder.  
- Includes raw sales transactions with fields like **Date**, **Store_ID**, **Item_Category**, **Quantity**, **Sales**, **Inventory Levels**, etc.

---

## Tools and Technologies
- **SQL** – Data extraction and aggregation.  
- **Python (Pandas, Matplotlib)** – Data cleaning and visualization.  
- **Power BI** – Interactive dashboards to monitor performance.  
- **Git/GitHub** – Version control and documentation.

---

## Project Structure
```
Commercial-Store-Sales-Analysis/
├── data/                       # Raw and processed datasets
├── notebook/                   # Jupyter notebooks for analysis
├── dashboard/                  # Power BI dashboards (.pbix)
├── images/                     # Exported visuals and charts
├── README.md                   # Project documentation
└── .gitignore                  # Files to ignore in version control
```

---

## Data Cleaning & Preparation
- Handled **missing data**, **duplicates**, and **anomalous values**.  
- Transformed dates, standardized category naming, computed metrics like average daily sales and inventory turnover.  
- Generated the cleaned dataset used in visualizations.

---

## Exploratory Data Analysis (EDA)
- Sales trends over time (daily/weekly/monthly).  
- Best and worst performing product categories.  
- Correlation between inventory levels and sales.  
- Region-wise performance comparison.

---

## Research Questions & Key Findings
1. Which categories generate the most consistent revenue?  
2. Which stores face inventory stockouts or overstocks the most?  
3. Seasonal buying pattern insights.  
4. Channels (online vs offline) performance.  

**Key Insights:** (summarize your findings here—e.g., “Electronics category has 20% higher daily sales but 15% more stockouts compared to Clothing.”)

---

## Dashboard/Model/Output
- **Power BI dashboard** showcasing KPI cards, category heatmaps, inventory vs sales charts, store comparisons.  
- Exported visuals available in the `images/` folder (e.g., `images/sales_trend.png`, `images/inventory_performance.png`).

---

## How to Run This Project?
1. Clone repository:  
   ```bash
   git clone https://github.com/Ayu0209/Commercial-Store-Sales-Analysis.git
   cd Commercial-Store-Sales-Analysis
   ```  
2. Open and run notebooks in the `notebook/` folder.  
3. Open `dashboard/your_dashboard.pbix` in Power BI Desktop.

---

## Results & Conclusion
- Reduced inventory waste by identifying slow-moving items.  
- Improved stock replenishment efficiency across stores.  
- Dynamic Power BI dashboard enables strategic planning at a glance.

---

## Future Work
- Implement inventory forecasting and reorder alerts using time-series models.  
- Add a web-based dashboard via Streamlit or Power BI Service.  
- Integrate real-time data feeds from sales systems for live analytics.

---

## Author & Contact
**Author:** Ayushi Kedia  
📧 Email: your.email@example.com  
🔗 GitHub: [Ayu0209](https://github.com/Ayu0209)
