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

## Sales Forecasting

![c3](https://github.com/DivyanshaSingh/ADIDAS-US-SALES-FORECASTING-PowerBI-DASHBOARD/assets/119395726/40133c5b-aa4e-4bf9-bb47-029f8b2c20e6)

## Project Insights
## Project Insights

- **Retailer Analysis:** West gear in lead with 25% of units sold.
- **Sales Method:** Major stakes of 0.36 billion or 360 million observed via In-store sales method.
- **Product Performance:** Leading product is Men's street footwear with 0.209bn in sales followed by women's apparel, men's athletic footwear and so on. Women's athletic footwear needs attention as in comparison to men's athletic footwear, it is fairly low.
- **Geographical Analysis:** West in lead with 30% and northeast is also following up; we can match them with appropriate marketing strategies.
- **Price Sensitivity:** By analysis, I found price per unit is more likely to decrease when sum of units sold is 25 or less than otherwise (Average: 45.32). On the other hand, Price per unit is more likely to increase when sum of units sold is more than 745 than otherwise (on average: 44.75).
- **Forecast:** Performed sales forecasting of next 15 days with confidence interval of 95%, with peak day for sales in next 15 days on January 08, 2022.

## Conclusion

By developing a sales forecasting dashboard incorporating the outlined KPIs and insights, Adidas can make data-driven decisions to optimize sales strategies, enhance operational efficiency, and ultimately drive revenue growth. Continuous monitoring and refinement of the forecasting models will enable the company to adapt to changing market conditions and consumer preferences effectively.


## DAX Formula
A new column was required to calculate the revenue:
```DAX
Revenue = ('Table 1 (Data Sales Adidas)'[Price per Unit] * 'Table 1 (Data Sales Adidas)'[Units Sold])


