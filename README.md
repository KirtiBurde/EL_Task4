# EL_Task4
**Slide 1: Dashboard of Bicycle Sales Data**

link(https://github.com/KirtiBurde/EL_Task4/blob/main/Dashboard_Slide1.png)

Explanation:
This dashboard is designed to provide a high-level overview of bicycle sales performance across countries, products, and customer segments. It combines KPI tracking, product-level analysis, and time-based trends to help assess overall business health.

Dashboard Components and Their Meanings:

1. Top Cards (Top Center-Right):

Count of Country: 5 – Sales are happening in 5 different countries.

Average Units Sold: 1.61K – Per transaction or per customer.

Average Sale Price: $118.43 – Useful for understanding price positioning.

2. Sum of Profit by Product (Donut Chart - Top Left):

Top Products by Profit:

Paseo leads with 4.8M (28.4%)

Followed by Carretera, Montana, and Velo

Insight: Focus on Paseo and Carretera for future promotions or inventory prioritization.


3. Sum of Sales by Country (Tree Map - Middle Left):

Top Countries: United States of America, Canada, France, Germany, Mexico

Insight: The U.S. and Canada are the biggest contributors. These markets should be prioritized for marketing and supply chain efficiency.


4. Sales by Segment and Product (Stacked Bar Chart - Middle Center):

Shows how different segments (like Government, Enterprise, etc.) contribute to product sales.

Insight: Government segment buys mostly Carretera and Paseo

Midmarket and Channel Partners have lower engagement — potential opportunity areas


5. Line Chart – Sales & Profit by Segment (Bottom Center):

Shows the trend of total sales vs. profit by customer segment.

Insight: Government and Small Business segments are highly profitable.

Enterprise and Midmarket segments are lagging in both sales and profit.


6. Goal Tracking (Right Side KPIs):

Metric	Actual	Goal	Result

Profit	2.03M	2.0M	- Goal Achieved (+1.29%)
Gross Sales	1.25M	1.3M	- Below Target (−3.78%)
Units Sold	1.02M	1.0M	- Goal Achieved (+2.34%)


Insight: Although sales revenue slightly missed the goal, both profit and units sold exceeded expectations.

Indicates potential pricing or cost efficiency strategies working in favor.

7. Page Navigation Button (Bottom Left):

It will redirect the user to the next page where the detailed analysis of sales is presented.

Actionable Insights:

1. Top-Performing Products: Paseo and Carretera should receive investment for promotions and stock.

2. Underperforming Segments: Enterprise and Midmarket segments need investigation—consider marketing campaigns or partnership offers.

3. Country-Level Focus: U.S. and Canada are the strongest markets. Explore expansion or deeper penetration in other countries.

4. Pricing Strategy Success: Average sales price remains high while units sold targets are achieved, suggesting a well-balanced pricing model.


**Slide 2: Detailed Sales analysis**
link(https://github.com/KirtiBurde/EL_Task4/blob/main/Dashboard_Slide2.png)
Explanation:This Power BI dashboard titled "Sales Analysis" presents multiple visualizations summarizing sales data across various dimensions such as time, country, product, segment, and discount bands. Here's an explanation of each visual and key insights:




1. Sum of Units Sold by Discount Band (Pie Chart)

What it shows:
Distribution of total units sold based on the discount band applied (None, Low, Medium, High).

Insights:

Medium discounts account for the highest units sold (398.09K – 35.36%).

None and Low discount bands are close, at 33.73% and 23.26% respectively.

High discounts result in the lowest sales (only 7.65%).


Conclusion:
Moderate discounting (Medium) seems to be most effective for increasing units sold. Deep discounts (High) do not significantly boost sales volume and might be unnecessary.


---

2. Sum of Sales by Year and Month (Line Chart)

What it shows:
Trend of total sales over time, from September 2013 to November 2014.

Insights:

Sales exhibit fluctuations but an upward trend is noticeable.

A notable peak around May 2014 and again in late 2014.

Several dips (e.g., early 2014 and mid-2014).


Conclusion:
There is seasonal or campaign-based variation. Identifying what drove peaks (e.g., promotions, product launches) could help optimize future sales cycles.


---

3. Sum of Units Sold by Product and Country (Stream Chart)

What it shows:
Units sold per product type, broken down by country.

Insights:

Paseo is the top-selling product, especially strong in Canada and USA.

Carretera also shows decent sales, particularly in Germany and Mexico.

Some products like VTT and Velo have more balanced distribution.


Conclusion:
Some products have regional popularity. This can inform inventory and marketing strategies in specific countries.


---

4. Sum of Sales by Segment and Country (Stacked Bar Chart)

What it shows:
Sales distribution by business segment and country.

Insights:

Government and Small Business segments generate the most revenue.

USA contributes heavily across all segments.

Enterprise and Channel Partners segments have relatively low sales.


Conclusion:
Focus on Government and Small Business segments may yield higher returns, especially in the USA and Canada markets.


---

5. Button – "Click for Sales Analysis"

Likely a navigation button to switch between report pages or perform a drill-through for deeper analysis.



**Slide 3: Detailed Product Analysis**
link(https://github.com/KirtiBurde/EL_Task4/blob/main/Dashboard_Slide3.png)
Explanation: This Power BI dashboard is titled "Product Analysis" and focuses on analyzing profit, sales, and units sold by product and country. It helps identify which products perform best in terms of revenue and profitability, and where improvements may be needed.

1. Sum of Profit by Product and Country (Stacked Column Chart)

What it shows:
Breakdown of profit generated by each product, segmented by country.

Insights:

Paseo is by far the most profitable product, generating over 4 million in profit. The USA is a major contributor.

VTT and Amarilla are mid-range in profitability (~2.5M).

Carretera is the least profitable, though it still contributes across multiple countries.


Conclusion:
Paseo is the top performer in profitability across all regions. Carretera may need cost optimization or a strategic review.

2. Sum of Units Sold by Product (Bar Chart with Data Labels)

What it shows:
Total units sold for each product.

Insights:

Paseo leads with 338.24K units sold — more than double the next product.

Other products like VTT, Velo, Amarilla, Montana, and Carretera are closely clustered (around 145K–170K units).


Conclusion:
High unit sales of Paseo directly relate to its high profitability. However, other products like VTT and Velo, despite solid unit sales, don’t match Paseo's profit margin — indicating possible lower pricing or higher costs.

3. Sum of Sales by Product (Bar Chart)

What it shows:
Revenue (sales value) generated per product.

Insights:

Paseo once again leads, followed by VTT, Velo, and Amarilla.

The sales distribution is similar to the unit distribution — products with higher units also have higher sales.


Conclusion:
Sales and units are strongly correlated, but Paseo likely has a higher price point or better margin, making it superior in both sales and profit.

Button – "Click for Profit Analysis"

Likely a navigation button to explore more detailed profit-related metrics or drill-through to individual product profit views.


**Slide 4: Detailed Profit Analysis**
link(https://github.com/KirtiBurde/EL_Task4/blob/main/Dashboard_Slide4.png)
Explanation: This Power BI dashboard is titled “Profit Analysis” and focuses on understanding how profit varies across different segments, countries, and products. The goal is to identify what drives profitability and where losses or inefficiencies occur.

1. Sum of Profit by Segment (Bar Chart)

What it shows:
Total profit generated by different customer segments.

Insights:

Government segment is the most profitable at 11.39M.

Small Business is second with 4.14M.

Enterprise segment shows a loss of -0.61M, which is a red flag.

Channel Partners and Midmarket have relatively smaller profit contributions.


Conclusion:
The Government and Small Business segments are key profit drivers. The Enterprise segment is incurring losses and needs urgent attention—perhaps due to pricing, high support costs, or low margins.

2. Sum of Profit by Country (Bar Chart)

What it shows:
Total profit distribution across countries.

Insights:

France and Germany are the most profitable countries (each above 4M).

Canada, USA, and Mexico follow with decreasing profitability.

All countries are profitable — no losses reported here.


Conclusion:
Europe (France & Germany) is a strong market. Performance in North America (especially the USA and Mexico) can be improved.

3. Sum of Profit by Product (Line Chart)

What it shows:
Profit by individual products.

Insights:

Paseo is again confirmed as the most profitable product (~5M).

VTT, Amarilla, and Velo have moderate profits.

Carretera and Montana are the least profitable.


Conclusion:
Focus on maximizing Paseo’s sales. Carretera and Montana may need discontinuation, rebranding, or cost optimization.

4. Average, Min, and Max Profit (Gauge Visual)

What it shows:

Average profit per product: 24.13K

Minimum profit: -40.62K (loss on a product or transaction)

Maximum profit: 262.20K


Insights:

Wide profit range shows inconsistent profitability across products or segments.

Negative profit confirms there are some losses (likely linked to Enterprise or low-performing products).

