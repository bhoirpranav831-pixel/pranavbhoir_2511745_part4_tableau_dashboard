# pranavbhoir_2511745-_part4_tableau_dashboard

## TASK 1 : CONNECT AND INSPECT DATA

order date and ship date are treated as valid date fields.
sales, profit, discount, and quantity are treated as numerical measures.
region, state, city, category, sub-category, segment, and ship mode are treated as categorical dimensions.
postal Code is treated as a geographic identifier.
returned field (if present) is treated as a binary flag for return analysis
each Order ID represents a unique order unless duplicate records exist for multiple products within the same order
missing values if any assumtion  to be minimal and do not materially affect dashboard insights

README Requirements

1. business summary

goal of this project is to create an interactive executive dashboard that will enable the management of the retail sector to measure the overall performance of the business. Through this dashboard, one can analyze sales trends, profitability, performance of regions, segments of customers, shipping efficiency, effect of discounts, and return trends.

2. Dataset Description

The dataset contains retail sales transaction data, including:

Order Date
ship Date
Sales
Profit
Discount
Quantity
Region
State
Category
Sub-Category
Customer Segment
Ship Mode
Returned Orders
Customer Information

3. Tableau Workbook Description

tableau workbook (executive_dashboard.twbx) comprises an executive dashboard consisting of several visualizations that help derive meaningful information about the performance of the business. The visualization includes KPI cards, trend analysis, region-wise analysis, profitability analysis, shipping analysis, discount analysis, and return analysis.

4. Calculated fields created

following calculated fields were created in Tableau:

calculated field : profit margin 
purpose :to calculate percentage of profit earn from total sales 

calculated field : cost
purpose : calculate cost as sales - profit 

calculated field : average order value 
purpose : calculate average sales value per order 

calculated field : return rate 
purpose : calculate percentage of return order out of total order

calculated field : shipping delay bucket
purpose : categorizes delivery days into fast, standard and delayed shipping groups

5. dashboard components

KPI total sales
KPI total profit
KPI profit margin
sales trend view
regional performance view
category profitability view
customer segment view
shipping performance view
discount vs profit view
return analysis view

6. Filters and Interactions Used

-Interactive Filters

region
category 
customer 
order date
ship mode

-Dashboard Interaction
dashboard filter activity enables the user to choose a region or category, and all relevant charts are automatically updated.

7. Key Business Insights

sales increase between 2024 and 2025 suggesting company growth.
south zone had the highest sales and profit.
technology is the most profitable category of products.
home office customers provided the highest sales and profit.
high discounts lower profits.
standard Class shipping takes the longest time to deliver.
furniture has the highest return rate.
reducing high discounts and returns would improve profitability.

8. Dashboard story summary

dashboard gives a summary report on the overall performance of the business for its leaders. despite continued growth in sales and profit there are chances for improvement in terms of extending some of the profitable products and markets but also facing difficulties like over discounting shipping problems, and product returns.


9. Assumptions and Limitations

-assumptions

data is correct and complete.
returns are properly classified.
number of delivery days is based on order and ship dates.
profit margin and return rate are calculated with provided data.

-limitations

dashboard uses historical data only.
customer satisfaction and other external factors are not considered.
forecasting and other predictive analysis are beyond the scope of this dashboard.
analysis results are determined by the data source's accuracy and completeness.

10. Screenshots Included

following screeshits are in repository : 

full_dashboard.png
sales_trend_view.png
regional_performance_view.png
category_profitability_view.png
filter_interaction_view.png
