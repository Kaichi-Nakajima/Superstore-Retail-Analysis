# Superstore-Retail-Analysis
An exploratory analysis of retail sales data to identify performance trends, revenue-driving customer segments and products, customer concentration, and seasonal patterns. The project uses Python and pandas to clean and analyze the data, then translates findings into business recommendations.

### Objective
Analyze sales trends, customer segments, products, and purchasing patterns to identify the main drivers of revenue and where the business should focus its sales and customer efforts.

### Questions Explored
- How do sales change over time, and are there recurring seasonal patterns?
- Which customer segments contribute the most sales?
- Which categories and products generate the most revenue?
- Do products appearing in more orders also generate more revenue?
- How concentrated is revenue among customers, and how often do they purchase?

### Data and Approach
The analysis uses order, customer, product, segment, date, and sales fields. The dataset was checked for missing values and duplicate records. Order dates were converted for time-based analysis, and revenue was compared across customer segments, products, customers, and months.

### Executive Summary
Out of the customer segments, Consumer generated the most sales ($560.5K), followed by Corporate ($314.4K) and Home Office ($229.9K). Home Office had the highest average sales per order at about $530, compared with $461 for Corporate and $441 for Consumer. This suggests the segments differ in both sales scale and typical order value.

Revenue is concentrated among top customers: the top 10% account for 38.7% of sales. The highest-sales customer contributed about $24.2K. Customers placed an average of 3.2 orders in the observed period, though the analysis window may not capture their complete histories.

Product results show a distinction between order frequency and sales per order. Some products appear in many orders, while the most extreme sales-per-order products appear in only one or two orders. Those products should not be described as the leading revenue drivers until they are compared using total sales and order count.

Monthly sales are uneven, with noticeable peaks around September and late in the year. The year-by-year chart suggests stronger sales in parts of Q4, but the peaks vary in size and timing.

### Recommendations
Prioritize retention of high-revenue customers as they account for 38.7% of sales. To reinforce this, maintain focus on Consumer as the main target as they are the largest sales segment while also exploring whether Home Office's high sales per order can be expanded.

Use product and seasonal findings to guide planning only after confirming that the patterns recur. Some high-sales products appear in very few orders, and monthly peaks vary across years. Avoid treating one-off large transactions as reliable demand or making inventory changes from a single peak.

Note: This dataset reports sales revenue but does not include product costs or discounts, so it cannot show gross or net profit. Analyze profitability with cost and expense data before making final decisions about product priorities, promotions, or customer investments.
