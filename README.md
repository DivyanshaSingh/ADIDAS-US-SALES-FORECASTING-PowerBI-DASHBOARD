Click To Proceed
https://github.com/DivyanshaSingh/ADIDAS-US-SALES-FORECASTING-PowerBI-DASHBOARD/issues/1#issue-2158721564
![c1](https://github.com/DivyanshaSingh/ADIDAS-US-SALES-FORECASTING-PowerBI-DASHBOARD/assets/119395726/63ba4175-341e-4669-8ddb-2ec4e68aa6da)

![c2](https://github.com/DivyanshaSingh/ADIDAS-US-SALES-FORECASTING-PowerBI-DASHBOARD/assets/119395726/412aecaf-a536-47dd-afb1-960f5f45ba0d)
# Table of Contents
1. [Objective](#objective)
2. [Process](#process)
3. [Dashboard Requirements](#dashboard-requirements)
4. [DAX Formulas](#dax-formulas)
5. [Sales Forecasting](#sales-forecasting)
6. [Project Insights](#project-insights)
7. [Conclusion](#conclusion)

## Objective
Leverage advanced business analytics skills and Power BI expertise to develop an interactive sales forecasting dashboard for Adidas US sales data. Utilize data-driven insights to inform strategic decisions, optimize sales strategies, and drive revenue growth through actionable analytics and dynamic visualizations.

## Process
To propel organizational growth, efficiency, and customer satisfaction, I provide:
1. Expertise in KPI identification and intuitive dashboard creation with interactive visuals and advanced filtering capabilities.
2. Valuable insights on sales strategy efficacy through charts, enabling informed decision-making for enhanced performance.
3. Proficiency in historical data analysis for accurate sales forecasts, facilitating proactive planning and strategic decision-making, ultimately driving goal achievement.
In summary, I deliver actionable intelligence empowering strategic decision-makers to achieve organizational objectives efficiently.

## Dashboard Requirements
- **Primary KPI's:** Units Sold, Price Per Unit, Total Sales, Operating Profit, Operating Margin.
- **Secondary KPI's:** Region, Retailer, Sales Method, Products.
- Market share of total sales by Region, Retailer, Sales method, Product.
- Trend of unit price on different product categories.
- Trend of Price Sensitivity based on Product and Region and also by operating Profit & Margin.
- Sales Forecasting with respect to Invoice Date and Total Sales.

## DAX Formula
A new column was required to calculate the revenue:
```DAX
Revenue = ('Table 1 (Data Sales Adidas)'[Price per Unit] * 'Table 1 (Data Sales Adidas)'[Units Sold])
