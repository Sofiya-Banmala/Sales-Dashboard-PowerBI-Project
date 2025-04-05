# Sales-Dashboard-PowerBI-Project

## T&EO Analytics and Insights 

This Power BI dashboard project was created to explore and analyze product sales performance along with customer-related insights. The process started with data cleaning, followed by building visuals that tell a complete story. It includes interactive features and smart visuals like outlier detection, key drivers, and trend analysis.

### Overview

The report focuses on:
- Total Sales, Total Cost, and Overall Profit
- Monthly trends in Profit and Profit Percentage
- Customer Occupation and Age Group analysis
- Product-wise profitability and sales performance
- Key factors that impact profitability
- Outlier detection using the IQR (Interquartile Range) method

### Key Features

- **Data Preparation**: Used Power Query to clean and transform the raw dataset before analysis.
- **Custom DAX Measures**: Created fields like `Profit`, `%Profit`, and dynamic calculations to make the report more insightful.
- **Advanced Visuals**:
  - **Key Influencers** to understand what drives changes in profit percentage
  - **Decomposition Tree** for drilling into product performance at a granular level
  - **Scatter Plot** with IQR-based logic for identifying profit outliers
- **Interactive Design**:
  - Dynamic dropdown slicers (e.g., Outlier vs Normal)
  - Filters for Year, Month, State
  - Hover tooltips with detailed product insights

#### Main Dashboard  
![Main Dashboard](sales dashboard.png)

#### Outlier Detection View  
![Outlier Detection](image2.png)

#### Key Influencers + Decomposition Tree  
![Key Influencers](image3.png)

---

### GIF Preview

Here’s a quick walkthrough of the interactive dashboard in action:

![Dashboard GIF](dashboard-preview.gif)

---

### About This Project

This dashboard was built as part of my Power BI learning journey. It allowed me to apply end-to-end business analytics skills — from preparing data and building DAX measures to designing visuals and uncovering insights through interactivity and statistical logic.

Feel free to explore, fork, or suggest improvements!
