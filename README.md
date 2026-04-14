# Executive Sales Intelligence Dashboard: Python, SQL & Power BI
## 📌 Project Overview
This project serves as the final layer of a comprehensive data engineering pipeline. Moving beyond data movement, this repository focuses on Diagnostic and Strategic Analytics. I transformed raw data into actionable business intelligence by performing deep-dive EDA in Python, aggregating complex KPIs in AWS Athena, and designing an interactive Executive Dashboard in Power BI.

## 🛠️ Tech Stack
Diagnostic Analytics: Python (Pandas, Seaborn, Matplotlib, Plotly)

Big Data Aggregation: SQL (Amazon Athena / Presto)

Business Intelligence: Microsoft Power BI Desktop

Environment: Google Colab & AWS Cloud

## 🔍 Phase 1: Python Diagnostic Analytics
In the Global_Sales_Analytics.ipynb notebook, I performed advanced analysis to uncover business patterns that raw numbers hide:

Pareto Analysis (80/20 Rule): Identified that 20% of products drive 80% of total revenue.

Price Elasticity: Analyzed the correlation between Unit_Price and Units_Sold to understand consumer sensitivity.

Growth Tracking: Calculated Month-over-Month (MoM) Growth and Cumulative Revenue to visualize business momentum.

Profit Drain Analysis: Isolated specific categories where high revenue did not translate to high profit margins.

## ⚡ Phase 2: The SQL Intelligence Layer (Athena)
To prepare the data for the BI layer, I wrote an optimized SQL view in Amazon Athena using Window Functions (LAG, OVER). This pre-calculated complex growth metrics at the database level, ensuring the Power BI dashboard remains high-performance.

## 📊 Phase 3: Executive Power BI Dashboard
The final output is an interactive "Single-Pane-of-Glass" solution for stakeholders.

Real-time KPI Tracking: Instant visibility into Revenue and Profit totals.

Regional Drill-Downs: Interactive bar charts showing performance by territory.

Dynamic Slicing: Stakeholders can filter the entire report by Salesperson or Category to identify specific team performance.

## 🖼️ Project Visuals
## 1. Executive Dashboard (Power BI)
![image](https://github.com/NivedhReddy2048/Cloud-Analytics-BI-Dashboard/blob/main/Visualization_PowerBi.png?raw=true)
## 2. Strategic Diagnostic Audit (Python)
![image](https://github.com/NivedhReddy2048/Cloud-Analytics-BI-Dashboard/blob/main/Python_Pareto_Analysis.png?raw=true)
## 3. The Big Data Aggregation Engine (AWS Athena)
![image](https://github.com/NivedhReddy2048/Cloud-Analytics-BI-Dashboard/blob/main/Visualization_PowerBi.png?raw=true)
## 4. Market Sensitivity & Profit Study (Python)
![image](https://github.com/NivedhReddy2048/Cloud-Analytics-BI-Dashboard/blob/main/Visualization_PowerBi.png?raw=true)

## 🚀 How to Use
Review the notebooks/ folder for the Python EDA logic.

The Athena result.csv contains the pre-aggregated data for the dashboard.

Open the .pbix file in Power BI Desktop to interact with the live report.
