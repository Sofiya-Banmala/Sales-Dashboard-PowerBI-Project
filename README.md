# Sales-Dashboard-PowerBI-Project

## T&EO Analytics and Insights

![Dashboard GIF](https://github.com/Sofiya-Banmala/Sales-Dashboard-PowerBI-Project/blob/main/dashboard.gif)

This project is a comprehensive Power BI dashboard developed to analyze the sales performance of products alongside customer behavior insights. The dashboard walks through the entire BI process—from cleaning and transforming raw data to building insightful visual reports and interactive experiences. It's built with a focus on clarity, interactivity, and depth in analysis.

---

### Overview

The dashboard was created to deliver end-to-end analytics covering the following areas:

- **Total Sales, Total Cost, and Overall Profit**: Summarized at the top of the report for quick insights.
- **Monthly Trends**: Profit and %Profit are tracked over time to observe seasonal performance or consistent growth.
- **Customer Analysis**: Visuals break down customer data by age group and occupation to understand the target demographic.
- **Product-Level Breakdown**: Product-wise sales and profitability are shown in a structured table with hierarchical views.
- **Key Profit Drivers**: Using built-in AI visuals, the report identifies what influences profit margins the most.
- **Outlier Detection**: Implements IQR-based logic to highlight products that perform significantly outside the norm.

---

### Key Features

#### Data Preparation

All raw data was cleaned using Power Query in Power BI. This involved removing nulls, fixing data types, renaming fields, and creating calculated columns to support analysis.

#### Custom DAX Measures

Several custom measures were built using DAX (Data Analysis Expressions), including:
- `Profit` = Total Sale - Total Cost
- `%Profit` = (Profit / Cost) * 100
- MoM% (Month-over-Month % change)
These metrics help provide deeper financial insight beyond just raw sales numbers.

#### Advanced Visuals

- **Key Influencers**  
  This AI visual helps uncover what product or customer characteristics are most closely associated with increases in profit percentage.

- **Decomposition Tree**  
  Used to drill down into specific product contributions to overall profit, offering a flexible way to explore data by category or item.

- **Outlier Detection (Scatter Plot + IQR Logic)**  
  Profit outliers were detected using statistical logic (Interquartile Range). Products that performed far above or below the normal profit range are flagged and displayed in a separate view for anomaly tracking.

- **Interactive Filters**  
  Users can slice the data by Year, Month, State, Outlier Flag, and more. A clean dropdown for Outlier classification (Normal vs. Outlier) was also added to improve filtering UX.

---

### Screenshots

#### Main Dashboard  
![Main Dashboard](https://github.com/Sofiya-Banmala/Sales-Dashboard-PowerBI-Project/blob/main/sales%20dashboard.JPG)

#### Outlier Detection View  
![Outlier Detection](https://github.com/Sofiya-Banmala/Sales-Dashboard-PowerBI-Project/blob/main/outlier.JPG)

#### Key Influencers + Decomposition Tree  
![Key Influencers](https://github.com/Sofiya-Banmala/Sales-Dashboard-PowerBI-Project/blob/main/AI.JPG)

---

### About This Project

This dashboard was built as part of a hands-on learning journey to sharpen my Power BI skills. It offered the opportunity to practice:
- Transforming and shaping data using Power Query
- Writing DAX formulas to derive custom business metrics
- Designing visualizations that focus on clarity and interactivity
- Using Power BI’s AI capabilities for smart, guided analysis
- Applying statistical logic to detect outliers and patterns

The project showcases a full-cycle analytics process—from data prep to insights delivery—and is part of my growing portfolio in business intelligence and reporting.

Feel free to clone, explore, or provide suggestions for improvement!
