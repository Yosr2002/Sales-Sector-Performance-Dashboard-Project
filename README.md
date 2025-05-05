![1002](https://github.com/user-attachments/assets/44f5d6d8-3380-4a03-b530-ab3b8b9a4723)
![1001](https://github.com/user-attachments/assets/733fa3fa-5a8d-46a8-90e6-8ff92a354612)
![1004](https://github.com/user-attachments/assets/943abdb3-f50d-439e-89a6-12ae969bf35e)
![1003](https://github.com/user-attachments/assets/91dd5afc-86e6-4177-b44c-8579537703d9)
📊 CRM Sales Performance Analysis
📝 Project Overview
This project is a comprehensive CRM data analysis conducted using Power BI. It focuses on evaluating company, product, region, and sales performance across various sectors. The goal is to generate actionable insights that help decision-makers enhance sales efficiency and revenue growth.

🎯 Objectives
Analyze sales performance metrics such as revenue, won/lost deals, and expected revenue.

Identify top-performing sectors, products, sales agents, and regional offices.

Visualize deal trends over time and across sales stages.

Detect key patterns that can guide future sales strategy.

📁 Dataset Description
The dataset is composed of four tables:

Companies Table
Columns: Company Name, Number of Employees, Office Location, Expected Revenue, Sector, Year Established.

Opportunities Table
Columns: Opportunity ID, Sales Agent, Product, Company Name, Deal Stage, Engaged Date, Close Date, Close Value, Sector, Office Location, Manager, Regional Office.

Products Table
Columns: Product, Sales Price, Series.

Sales Team Table
Columns: Manager, Regional Office, Sales Agent.

🛠️ Data Preparation & Cleaning
Merged related tables using keys (e.g., company name, sales agent).

Removed duplicate and null records.

Extracted date fields like Year, Quarter, Month from Close Date.

Calculated new columns:

Deal duration in months (Close Date - Engaged Date)

Revenue Growth

Expected & Lost Revenue

Created relationships and star schema model in Power BI.

📊 Dashboards
Executive Overview

KPIs: Total Revenue, Number of Deals, Won Deals %, Achieved Revenue %

Visuals: Revenue by Quarter, Deal Status Pie, Top Companies/Sectors by Revenue

Filters: Sector, Company Name

Sales Performance

Focus: Sales Agent Activity, Deal Stages, Revenue per Agent

Visuals: Deals by Status & Agent, Win/Lost Deals by Quarter, Closure Time Analysis

Filters: Date, Sector, Status

Sector Performance

Focus: Sector-Wise Deal and Revenue Distribution

Visuals: Revenue, Expected, and Lost Revenue by Sector; Revenue Growth; Product Sales

Dynamic Titles based on filters (e.g., Medical Sector Performance)

Product & Regional Performance

Focus: Product Sales by Region and Manager Effectiveness

Visuals: Top/Bottom Products, Revenue by Region, Manager vs. Revenue, Team Size

📌 Key Insights
Certain sectors such as Medical and Technology consistently lead in total revenue and won deals.

Longer deal durations often correlate with higher loss rates.

Sales agents with faster closure times and fewer pending deals perform better overall.

Product performance varies significantly across regions and sectors.

Managers with larger teams don't always generate more revenue—team efficiency matters more than size.

💡 Tools Used
Power BI for data modeling and visualization



DAX for custom KPIs and time intelligence metrics

