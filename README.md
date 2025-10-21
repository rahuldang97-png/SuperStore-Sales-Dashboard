# 📊 SuperStore Sales Dashboard

This repository contains an interactive **Power BI Dashboard** built using the **Superstore Sales dataset**.  
The dashboard provides a comprehensive overview of sales, profit, customer segments, and regional performance, helping identify trends and key business insights.

---

## 🧠 Project Objective

The primary objective of this project was to:
- Analyze sales and profit performance over time
- Compare regional and category-wise profitability
- Study the effect of discounts on overall margins
- Identify top-performing customers and products
- Enable quick data-driven decision-making through interactive visuals

---
## 🧹 Data Cleaning & Preparation

Data cleaning was performed in **Power BI Power Query Editor**:
- Removed duplicate and null entries
- Standardized date formats
- Deleted 2 columns that contained only blank values.
- In the “Returns” column, replaced all #N/A values with 0 for consistency in calculations.

## DAX

- Only one DAX measure was used to create a KPI card:
Average Delivery Day = DATEDIFF('SuperStore_Sales_Dataset'[Order Date],'SuperStore_Sales_Dataset'[Ship Date],DAY)
- Purpose- This KPI helps evaluate logistics efficiency and delivery performance=


---
## Data Analysis
- Incorporated data analysis
techniques, specializing in time
series analysis, to deliver valuable
insights, accurate sales forecasting,
and interactive dashboard
creation, driving business success.

---
## Snippets
- Page1
[Dashboard Page1](/Images/page_1.png)

- Page2
[Dashboard Page2](/Images/page_2.png)


```
Superstore-Sales-Dashboard
│
├── Dashboard/
│   └── Dashboard_sales.pbix
│
├── Dataset/
│   └── SuperStore_Sales_Dataset.csv
│
├── README.md
└── images/
    └── dashboard_preview.png

```
