Pizza Sales Analysis Using Excel 

Project Overview

This project analyzes pizza sales data using Microsoft Excel Pivot Tables. The objective is to understand sales performance across different dimensions such as month, pizza category, pizza size, pizza type, quarter, season, and hour of the day.

The analysis helps identify sales trends, customer preferences, peak sales periods, and business opportunities for improving revenue and operational efficiency.

Objectives

The project aims to:

* Analyze total sales performance.
* Identify the best-performing pizza categories and sizes.
* Understand monthly sales trends.
* Determine peak sales hours.
* Analyze sales by quarter and season.
* Generate insights and recommendations based on customer purchasing behavior.

Dataset Description

The dataset contains pizza sales transaction records with information such as:

| Column         | Description                                        |
| -------------- | -------------------------------------------------- |
| pizza_id       | Unique pizza transaction ID                        |
| order_id       | Unique order ID                                    |
| pizza_name_id  | Pizza type identifier                              |
| quantity       | Number of pizzas ordered                           |
| order_date     | Date of purchase                                   |
| order_time     | Time of purchase                                   |
| unit_price     | Price per pizza                                    |
| total_price    | Total sales amount                                 |
| pizza_size     | Pizza size (S, M, L, XL, XXL)                      |
| pizza_category | Pizza category (Classic, Chicken, Supreme, Veggie) |
| Ingredients    | Pizza ingredients                                  |


Data Preparation

Before analysis, the following data preparation tasks were performed:

1. Date Processing

The order date column was converted into date format and used to derive:

* Month
* Quarter
* Season
* Year

2. Time Processing

The order time column was used to extract sales hours for hourly analysis.

3. Ingredient Handling

Pizza ingredients were separated into individual ingredient columns for easier analysis.

---

Analysis Tasks Performed

Sales Analysis

1. Total Sales per Month
2. Total Sales per Category
3. Total Sales per Size

Sales Volume Analysis

4. Total Number of Sales per Month
5. Total Number of Sales per Category
6. Total Number of Sales per Size

Product Analysis

7. Number of Pizza Types Available
8. Total Sales per Pizza Type per Month

Time-Based Analysis

9. Total Sales per Hour
10. Total Sales per Quarter
11. Total Sales per Season
12. Total Number of Sales per Quarter
13. Total Number of Sales per Season

Comparative Analysis

14. Total Sales per Category per Month
15. Total Sales per Size per Month

Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Excel Date Functions
* Data Cleaning Techniques


Key Insights

Customer Preferences

* Certain pizza categories consistently generated higher sales than others.
* Medium and Large pizzas contributed the largest share of revenue.
* Some pizza types were significantly more popular than others.

Monthly Trends

* Sales varied across months, indicating seasonal demand patterns.
* Certain months recorded higher revenue and transaction volume.

Time Trends

* Sales peaked during specific hours of the day.
* Lunch and evening periods showed stronger customer activity.

Seasonal Trends

* Some quarters outperformed others in terms of revenue.
* Seasonal analysis revealed periods of stronger demand.

Recommendations

Inventory Planning

Stock ingredients based on demand patterns to reduce waste and avoid shortages during peak periods.

Promotional Campaigns

Run targeted promotions during low-performing months to increase customer purchases.

Product Strategy

Focus marketing efforts on top-selling pizza categories and sizes while reviewing the performance of lower-selling products.

Staffing Optimization

Schedule more staff during peak sales hours to improve customer service and order processing efficiency.

Seasonal Marketing

Develop seasonal offers and campaigns based on historical sales patterns to maximize revenue opportunities.


Conclusion

This project demonstrates how Excel Pivot Tables can be used to perform exploratory business analysis and uncover meaningful insights from sales data. The analysis provides valuable information for decision-making in sales planning, inventory management, staffing, and marketing strategy.

The project highlights the effectiveness of Microsoft Excel as a powerful tool for business intelligence and data analysis.
