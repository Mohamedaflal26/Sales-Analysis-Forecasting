# Sales-Analysis-Forecasting
<img width="1022" alt="Screenshot 2024-11-19 at 9 57 19 PM" src="https://github.com/user-attachments/assets/80e09e61-c638-4ff6-b7b3-cd70f25ae8d8">

<img width="1022" alt="Screenshot 2024-11-19 at 9 57 39 PM" src="https://github.com/user-attachments/assets/10ce021f-b8d3-49bc-b6a7-26f57ec4c302">


MY project on Sales Analysis & Forecasting demonstrates a structured approach to understanding sales trends and patterns using Python and pandas. Here's a summarized workflow of what I've accomplished and some insights based on my analysis:

1. Combining Monthly Sales Data
   
   Effectively combined data from 12 monthly CSV files into a single DataFrame (all_data). This allowed you to perform global analysis across all months.

2. Data Cleaning
   
    addressed common issues such as:

Removing rows with NaN values.

Filtering out invalid data (e.g., rows where "Order Date" starts with 'Or').

Converting columns to the correct data types (Quantity Ordered and Price Each).

3. Feature Engineering
   
 created new columns for further analysis:

Month: Extracted from the "Order Date" for monthly aggregation.

Sales: Calculated by multiplying Quantity Ordered and Price Each.

City: Extracted from the "Purchase Address" to analyze geographic sales performance.

Order Time: Parsed "Order Date" into hour and minute.

4. Analysis and Insights

a) Best Month for Sales:

Using a bar chart, you identified December as the month with the highest sales, possibly driven by holiday shopping.

b) City-wise Sales:

San Francisco emerged as the top-performing city in terms of revenue. This could guide targeted marketing and inventory management.

c) Time Analysis:

plotted the number of orders by hour, revealing peak hours. This insight is valuable for:

Optimizing advertising schedules.
Improving operational readiness (e.g., delivery services).
d) Frequently Bought Together:

By grouping products sold under the same Order ID, you found commonly purchased combinations. These can inform:

Bundling strategies.
Cross-selling opportunities.

5. Visualization
You used:

Bar Charts: For monthly and city sales.

Line Plots: To analyze ordering patterns by hour.

These visualizations make it easier to communicate insights to stakeholders.
