# kevin-cookie-dashboard
Power BI dashboard &amp; SQL + DAX for Kevin Cookie Company
**Kevin Cookie Company - Sale and Rush Delivery Dashboard**

**1. Project Overview**

This project was about analyzing the orders and revenue of Kevin Cookie Company. I built a Power BI dashboard to track daily and monthly performance, and also to see how much rush deliveries contribute to sales.

**2. Dataset**

I started with a CSV file of orders. To practice SQL, I imported it into PostgreSQL (public schema → cookies_orders table). Then I connected Power BI to PostgreSQL.
The main columns in the data:
order_id → order reference
customer_id → customer reference
order_date → when the order was placed
cookies_shipped → number of cookies shipped
revenue → total order revenue
rush → whether the order was rush (TRUE/FALSE)

**3. Steps I Took**

Loaded the data into PostgreSQL.
Brought it into Power BI and created a Calendar table.
Connected Calendar to the orders table on order_date.
Built DAX measures for total revenue, total orders, cookies shipped, rush vs non-rush, averages, cumulative revenue, etc.
Designed visuals: KPIs, line chart, pie/donut, and slicers.

**4. Dashboard**

KPIs → daily averages, monthly averages, peak revenue day, unique orders.
Line chart → revenue over time.
Pie/Donut → rush vs non-rush (orders and revenue).
Cumulative revenue table → long-term growth.
Slicers → rush status and date filters.

**5. Insights**

Data covers Dec 2024 – Jun 2025.
Daily orders ~1.6, monthly orders ~28.
Rush orders are more than half of all orders and bring in a big share of revenue.
Peak revenue day hit 14K+.
Average cookies shipped ~813 per day.

**6. Conclusion**

The dashboard makes it easier to keep track of orders and revenue, especially the effect of rush deliveries. It highlights trends, shows which days bring in the most revenue, and helps in planning production and shipping.
