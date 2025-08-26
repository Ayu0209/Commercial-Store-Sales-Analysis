# Commercial Store Sales Analysis

_Analyzing retail store sales data to extract insights into inventory performance and profitability using Jupyter Notebook, Python, and Power BI._

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
9. [Dashboard](#dashboard)  
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
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** → Data Cleaning & EDA  
- **Jupyter Notebook** → Analysis and visualization  
- **Power BI** → Dashboard and reporting  
- **GitHub** → Version control and project documentation

---

## Project Structure
```
Commercial-Store-Sales-Analysis/
│
│── 📂 data/                         
│   │── retail_sales_dataset.csv             # Original dataset
│   │── retail_sales_with_location.csv       # Original dataset with Location
│   │── final_sales.csv                      # Cleaned / transformed dataset
│
│── 📂 notebook/                 # Jupyter notebooks for EDA & analysis
│   │── Sales.ipynb
│
│── 📂 dashboard/                 # Power BI dashboard
│   │── sales_dashboard.pbix
│
│── 📂 visuals/                   # Exported plots, charts, and screenshots
│   │── blue gradient.jpg
│   │── page-1.jpg
│   │── page-2.jpg
│   │── symbol.jpg
│
│── 📄 README.md                 # Project overview, business problem, insights,etc
│── 📄 .gitignore                 # Ignore unnecessary files
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

## Dashboard
- **Power BI dashboard** showcasing KPI cards, category heatmaps, inventory vs sales charts, store comparisons.  
- Exported visuals available in the `images/` folder.
   **Dashboard Snapshot:**  

![Page-1](https://github.com/Ayu0209/Commercial-Store-Sales-Analysis/blob/main/images/page-1.jpg)  
![Page-2](https://github.com/Ayu0209/Commercial-Store-Sales-Analysis/blob/main/images/page-2.jpg)  
---

## How to Run This Project?
1. Clone repository:  
   ```bash
   git clone https://github.com/Ayu0209/Commercial-Store-Sales-Analysis.git
   cd Commercial-Store-Sales-Analysis
   ```  
2. Open and run notebooks in the `notebook/` folder.  
3. Open `dashboard/sales_dashboard.pbix` in Power BI Desktop.

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
👩‍💻 **Ayushi Kedia**    
📧 Email: ayushikediahm@gmail.com    
🔗 [LinkedIn](https://www.linkedin.com/in/ayushi-kedia-81bb7520b/)  

📧 Email: your.email@example.com  
🔗 GitHub: [Ayu0209](https://github.com/Ayu0209)
