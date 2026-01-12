#  Vendor Performance Analysis – Retail Inventory & Sales
Analyzing vendor efficiency and profitability to support strategic purchasing and inventory decisions using SQL, Python, and Power BI.
# Overview
This project evaluates vendor performance and retail inventory dynamics to drive strategic insights for purchasing, pricing, and inventory optimization. A complete data pipeline was built using SQL for ETL, Python for analysis and hypothesis testing, and Power BI for visualization.
# Business problem
Effective inventory and sales management are critical in the retail sector. This project aims to:

1) Identify underperforming brands needing pricing or promotional adjustments 

2) Determine vendor contributions to sales and profits

3) Analyze the cost-benefit of bulk purchasing

4) Investigate inventory turnover inefficiencies

5) Statistically validate differences in vendor profitability

# Tools & Technologies
> SQL (Common Table Expressions, Joins, Filtering)

> Python (Pandas, Matplotlib, Seaborn, SciPy)

>Power BI (Interactive Visualizations)

> GitHub

# Project Structure
vendor-performance-analysis/
│
├── README.md
├── requirements.txt
├── Vendor Performance Report.pdf
│
├── notebooks/                  # Jupyter notebooks
│   ├── exploratory_data_analysis.ipynb
│   ├── vendor_performance_analysis.ipynb
│
├── scripts/                    # Python scripts for ingestion and processing
│   ├── ingestion_db.py
│   └── get_vendor_summary.py
│
├── dashboard/                  # Power BI dashboard file
│   └── vendor_performance_dashboard.pbix

# Research Questions & Key Findings
1) Brands for Promotions: 198 brands with low sales but high profit margins

2) Top Vendors: Top 10 vendors = 65.69% of purchases → risk of over-reliance
   
3) Bulk Purchasing Impact: 72% cost savings per unit in large orders
   
4) Inventory Turnover: $2.71M worth of unsold inventory


