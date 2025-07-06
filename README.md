# Smart Inventory & Sales Insights

## Table of Content
- [Project Overview](project-overview)

- [Smart Inventory & Sales Insight Dashboard](smart-inventory-&-sales-insight-dashboard)

- [Data Sources](data-sources)

- [Data Tools](data-tools)

- [Data Cleaning & Preparation](data-cleaning-&-preparation)

- [Exploratory Data Analysis (EDA)](exploratory-data-analysis(e-d-a))

- [Data Analysis Approach](data-analysis-approach)

- [Results & Key Findings](results-&-key-findings)

- [Recommendations](recommendations)

- [Limitations](limitations)

- [Author information](author-information)


### Project Overview
---
This project presents an interactive inventory and sales dashboard that provides actionable insights to optimize stock management and improve profitability.
The dashboard is designed to assist business owners, inventory managers, financial analysts, and economists in making smart restocking decisions, reducing stockouts, and enhancing revenue forecasting. It demonstrates how economics and data analyst can merge to solve real world business problems using data-driven solutions.

##### Smart Inventory & Sales Insight Dashboard
![Screenshot 2025-07-06 175658](https://github.com/user-attachments/assets/a4e6fb3e-fd56-4257-be05-f037d44cb4fc)


### Data Sources

The dataset used for this project is a Simulated retail sales and inventory dataset (Excel format).

The dataset includes:
- Product Names
- Revenue
- Profit
- Inventory Available
- Store Location
- Dates(monthly)

### Data Tools
- Data Cleaning & Visualization: Power BI
- Data Preparation: Power Query (Power BI)
- Data Storage: Excel (.xlsx)

### Data Cleaning & Preparation
- Checked for and resolved missing values and column errors.
- Converted Year and Month columns to correct data types.
- Created new calculated columns:
    Stock Status (Low Stock vs. Good Stock),
    Recommended Restock Quantity
- Restock Priority based on sales volume and stock level.
- Removed duplicates and ensured proper data granularity.

### Exploratory Data Analysis (EDA)
Key Questions Explored Include:
- Which months have the highest or lowest revenue and profit?[View answer here1](view-answer-here1)
- What percentage of products are at risk of stockout?[View answer here2](view-answer-here2)
- Are there seasonal trends impacting sales?[View answer here3](view-answer-here3)

### Data Analysis Approach

##### Created KPIs for:
- Total Revenue
- Total Profit
- Total Low Stock Items
- Recommended Restock Quantity
- Applied conditional formatting to highlight low stock items.

##### Built:
- Revenue Trend Line Charts
- Profit Trend Line Charts
- Stock overview Pie Chart
- Smart Restock Recommendation Table

##### Used Power BI filters and slicers to dynamically explore:
- Contribution by Store locations

### Results & Key Findings
##### View answer here1
![Screenshot 2025-07-06 171921](https://github.com/user-attachments/assets/2514f0c5-bed8-4ec7-aab9-8d9506a7ded4)
-  The month of February has the lowest profit and revenue.While the month of April had the heighest revenue the month of march and april had the heighest profits
  
##### View answer here2
![Screenshot 2025-07-06 172341](https://github.com/user-attachments/assets/e51b2aa4-16ce-4c49-b6e1-09ffa73ae7f5)
- Low Stock Percentage: 19.42% of total products are at risk of stockout.
  
##### View answer here3
![Screenshot 2025-07-06 171921](https://github.com/user-attachments/assets/b72015e5-5536-45d3-84ed-4c286b34dcbf)
- Yes there are seasonal trends impacting sales. Revenue and profit dips in February, suggesting possible supply chain or demand fluctuation issues.

### Recommendations
- Prioritize restocking fast-selling, low-stock items immediately to avoid lost sales.
- Implement a smart inventory monitoring system to reduce the risk of stockouts.
- Continuously track low stock percentage as a key inventory health indicator.
- Align procurement planning with product sales trends to optimize stock levels.

### Limitations
- The dataset is simulated and may not fully reflect real-time business complexities.
- The sales volume and restock thresholds were based on assumed business rules.

### Author Information
##### Mmachi Goodness Paul-Emeka
##### Economist | Data Analyst | Power BI Specialist
##### Thanks for checking out this project feel free to reach out:
- Email:
 [mmachipaulemeka@gmail.com](mmachipaulemeka@gmail.com)
- Linkedin:
 [Mmachi Goodness Paul-Emeka](https://www.linkedin.com/in/mmachi-goodness-paul-emeka)

