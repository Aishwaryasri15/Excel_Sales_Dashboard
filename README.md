**Description:**

This chocolate sales dashboard provides a high-level overview of sales performance, including key performance indicators (KPIs) such as total sales, profit, and shipment volume. It also allows users to drill down into sales data by region, team, category, and individual product. The dashboard includes the following functionalities:

* **Sales Performance Summary:**  Displays total sales, profit, profit margin, total boxes shipped, and total shipments.
* **Regional Performance:**  Shows sales and profit figures by country, allowing users to compare performance across different regions. New Zealand is currently leading in sales at $3.78 million, while the United States has the highest profit margin at 70.6%.
* **Team Performance:**  Highlights the top-performing team in terms of sales (Yummies at $7.89 million) and allows users to compare sales figures between all four teams (Yummies, Delish, Jucies, and Tempo).
* **Product Category Analysis:**  Provides a slicer to filter sales data by category (bars, bites, and others). This enables users to identify which categories are driving sales.
* **Individual Product Performance:**  Allows users to view sales data for each product along with sorting options.

**Implementation Process:**

1. **Data Model & Calculations:** The data model is established, and DAX measures are created in Power Pivot.
2. **Slicers:** Category slicer is implemented.
3. **KPI Tiles & Country Maps:** KPI tiles display key metrics, dynamically updating with category selection. Country maps are integrated with formulas to highlight the top performer and display additional metrics.
4. **Sorting & Formatting:** Sorting options are added throughout the dashboard for both tables and charts. Conditional formatting like data bars and profit icons enhance visual representation.
5. **Team Performance:** Team-related pivots and a bubble chart showcase team performance. Sparklines visualize trends for the last 28 days.
6. **Product Performance:** Pivots with gauge charts analyze product category performance. A two-tier sorting table with linked product details and sparklines provides in-depth product insights.

**Insights:**

* **Strong Overall Performance:**  The dashboard showcases a total sales figure of $21.70 million with a profit margin of 69.2%, indicating strong overall sales performance.
* **Geographic Profitability:**  While New Zealand has the highest sales figures, the United States boasts the highest profit margin, suggesting an opportunity to optimize sales strategy in New Zealand to improve profitability.  
* **Yummies Team Leads:**  The Yummies team is currently leading in sales, and further analysis can be conducted to understand the reasons behind their success, which could be shared with other teams.
* **Category Breakdown:**  By using the category slicer, users can gain insights into which chocolate categories are most profitable and use this information to inform product development or marketing strategies.

**Key Performance Indicators (KPIs):**

* **Total Sales:** $21.70 million
* **Profit:** $15.02 million
* **Profit Margin:** 69.2%
* **Total Boxes Shipped:** 1344.6 thousand
* **Total Shipments:** 3791

