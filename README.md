# 📊 Profit Analysis Dashboard (Excel)

---

<p align="center">

![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-A100FF?style=for-the-badge&logo=powerquery&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-Data%20Summarization-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Calculations-F2C811?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Dashboard-Visualization-FF6600?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

<p align="center">
<b>An interactive Excel dashboard that analyzes company profit performance across products, regions, and time periods to support data-driven business decisions.</b>
</p>

---

# Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Tech Stack](#-tech-stack)
- [Project Workflow](#-project-workflow)
- [Data Cleaning](#-data-cleaning)
- [Data Analysis](#-data-analysis)
- [Dashboard Features](#-dashboard-features)
- [Key Metrics (KPIs)](#-key-metrics-kpis)
- [Key Insights](#-key-insights)
- [How To Use](#-how-to-use)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)
- [Business Impact](#-business-impact)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

#  Project Overview

Profit analysis is a critical part of business performance tracking. Companies need clear visibility into where profit is being generated, where margins are shrinking, and which products, regions, or segments need attention.

This project uses Microsoft Excel to build an interactive Profit Analysis Dashboard that transforms raw sales and cost data into actionable business insights.

The project combines:

- Data cleaning and preparation
- Pivot table-based analysis
- DAX / formula-driven KPIs
- Interactive slicers and filters
- Dashboard design and visualization

The dashboard helps:

- Track overall profit performance
- Compare profit across products, regions, and time periods
- Identify top and bottom performing segments
- Support faster, data-driven business decisions

---

#  Business Problem

Businesses often struggle to get a clear, consolidated view of profitability across different dimensions of their operations.

Common challenges include:

- Profit data scattered across multiple spreadsheets
- No easy way to compare performance across products/regions
- Manual reporting that is slow and error-prone
- Difficulty identifying loss-making areas quickly

Key questions addressed:

- Which products/regions generate the highest profit?
- How is profit trending over time?
- Where are margins declining, and why?
- Which segments need management attention?

---

#  Project Objectives

### Business Objectives

- Consolidate sales, cost, and profit data into one model
- Build KPIs to track profit performance
- Visualize profit trends across time, product, and region
- Enable interactive, self-service exploration via filters/slicers
- Deliver a decision-ready dashboard for stakeholders

---

#  Dataset Information

**Dataset Source:** Company sales/profit transaction data *(update with actual source)*

### Dataset Summary

| Metric | Value |
|----------|--------|
| Total Records | ** |
| Total Fields | ** |
| Time Period Covered | ** |
| Data Type | Structured Tabular Data (Excel/CSV) |

---

### Fields Included

| Field | Description |
|-----------|-------------|
| Order Date | Date of the transaction |
| Product / Category | Product name and category |
| Region / Segment | Sales region or business segment |
| Sales | Total sales revenue |
| Cost Price | Cost incurred per unit/order |
| Profit | Net profit generated |
| Profit Margin (%) | Profit as a percentage of sales |
| Quantity | Units sold |

*(Update the field list above to match the exact columns in your dataset.)*

---

#  Tech Stack

| Tool | Purpose |
|------------|----------|
| Microsoft Excel | Data storage, analysis, dashboarding |
| Power Query | Data cleaning and transformation |
| Pivot Tables & Pivot Charts | Data summarization and visualization |
| Excel Formulas / DAX | KPI and metric calculations |
| Slicers & Timelines | Interactive filtering |
| Conditional Formatting | Visual highlighting of performance |
| Git/GitHub | Version control and portfolio hosting |

---

#  Project Workflow

```text
Raw Sales/Profit Data
          │
          ▼
Data Cleaning (Power Query)
          │
          ▼
Data Modeling (Tables/Relationships)
          │
          ▼
Pivot Tables & Calculated Fields
          │
          ▼
KPI Calculations
          │
          ▼
Dashboard Design
          │
          ▼
Interactive Filters/Slicers
          │
          ▼
Final Profit Analysis Dashboard
```

---

#  Data Cleaning

Data preparation was performed before analysis and dashboard design.

### Tasks Performed

- Imported raw data into Excel
- Removed duplicates and blank records
- Handled missing/incorrect values
- Standardized date and category formats
- Created calculated columns (Profit, Margin %)
- Structured data into Excel Tables for dynamic referencing

---

#  Data Analysis

Analysis was conducted using Pivot Tables and formulas to uncover profit trends.

### Analysis Performed

- Profit trend over time (monthly/quarterly/yearly)
- Product-wise and category-wise profit comparison
- Region-wise / segment-wise profit distribution
- Profit margin analysis
- Top and bottom performing products/regions

---

#  Dashboard Features

- Interactive slicers for Region, Product, Category, and Time Period
- Dynamic Pivot Charts (bar, line, pie) for visual comparison
- KPI cards for at-a-glance performance tracking
- Conditional formatting to flag high/low profit areas
- Clean, single-page layout for executive reporting

---

#  Key Metrics (KPIs)

- Total Sales
- Total Profit
- Overall Profit Margin (%)
- Best Performing Product/Region
- Worst Performing Product/Region
- Month-over-Month / Year-over-Year Profit Growth

---

#  Key Insights

*(Update this section with the actual insights from your dashboard, e.g.:)*

- A specific region/product contributes the largest share of total profit
- Certain categories show declining margins despite stable sales
- Seasonal patterns significantly affect monthly profit trends
- A small percentage of products drive a disproportionate share of profit

---

#  How To Use

### Clone / Download Repository

```bash
git clone https://github.com/KartikKachwahe/Profit-Analysis-Dashboard-By-Excel.git
```

### Open the Dashboard

1. Navigate to the project folder
2. Open the `.xlsx` dashboard file in Microsoft Excel
3. Enable macros/content if prompted (if VBA is used)
4. Use the slicers and filters to explore profit data interactively

---

#  Repository Structure

```text
Profit-Analysis-Dashboard-By-Excel
│
├── Profit_Analysis_Dashboard.xlsx
├── Raw_Data.csv
├── Dashboard_Screenshot.png
├── README.md

---

#  Skills Demonstrated

### Excel

- Advanced Formulas
- Pivot Tables & Pivot Charts
- Power Query (ETL)
- Slicers & Interactive Filters
- Conditional Formatting

### Data Analysis

- Business/Profit Analysis
- KPI Design
- Trend Analysis
- Data Visualization

### Business Analytics

- Dashboard Design
- Executive Reporting
- Data-Driven Decision Support

### Tools

- Git Version Control
- GitHub Portfolio Management

---

#  Future Enhancements

- Automate data refresh using Power Query connections
- Add Power Pivot / DAX-based advanced KPIs
- Recreate the dashboard in Power BI for cloud sharing
- Add forecasting for future profit trends
- Include a What-If Analysis / scenario planner
- Add drill-through details for each KPI

---

#  Business Impact

Potential business benefits:

✅ Faster, consolidated profit reporting

✅ Clear visibility into high and low performing segments

✅ Reduced manual reporting effort

✅ Improved, data-backed decision-making

✅ Easy-to-share, self-service dashboard for stakeholders

✅ Better tracking of profit trends over time

---

#  Conclusion

This project demonstrates how Microsoft Excel can be used to build a complete, interactive Profit Analysis Dashboard — from raw data cleaning to KPI design and executive-level visualization.

The project covers a complete end-to-end analytics workflow:

- Data cleaning and preparation
- Data modeling and analysis
- KPI and metric development
- Interactive dashboard design
- Business insight generation

This dashboard can help organizations quickly identify profit drivers and make faster, more informed business decisions.

---

# 👨‍💻 Author

## Kartik Kachwahe

**Aspiring Data Scientist | Data Analyst | Machine Learning | SQL | Power BI | Python**

📧 Email: kartikkachwahe25@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/kartikkachwahe021

💻 GitHub: https://github.com/KartikKachwahe

---

## ⭐ Support

If you found this project useful, consider giving the repository a star.

Your support motivates future projects and helps others discover this work.

---

**Thank you for visiting this repository 📊**
