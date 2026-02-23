# Retail-Performance-Profitability-Intelligence-Dashboard

 Retail Performance & Profitability Intelligence
Developed by Mihir M. Patwardhan 

**1. Project Overview**
Retail Performance & Profitability Intelligence is a high-impact Power BI solution designed to transform raw transactional data into actionable executive insights. This dashboard provides a 360-degree view of retail operations, focusing on revenue streams, profit margins, and inventory distribution across the Indian market.

**2. Purpose & Business Problem**
In the competitive retail landscape, stakeholders often struggle to identify "profit leaks" and high-performing segments within vast datasets. This project was built to:

Identify underperforming regions and months with negative margins.

Analyze customer purchasing behavior to optimize marketing efforts.

Monitor inventory movement to prevent overstocking or stockouts in key categories.

**3. Tech Stack**
📊 Power BI Desktop: Core platform for data visualization and report orchestration.

📂 Power Query (M): Used for intensive ETL (Extract, Transform, Load) processes, including data cleaning and column normalization of the Orders and Details datasets.

🧠 DAX (Data Analysis Expressions): Engineered complex measures for dynamic KPIs, monthly variance analysis, and profit-to-sales ratios.

📝 Data Modeling: Implemented a Star Schema with a 1:N relationship between the Orders and Details tables to ensure optimized report performance.

4. Data Source
The analysis is based on a multi-table retail dataset containing:

Orders: Transactional records including Order IDs, Dates, Customers, and Geographical data (States/Cities).

Details: Granular line-item data including Amount, Profit, Quantity, and Product Categories/Sub-Categories.

5. Features & Business Insights
🛡️ Strategic Business Problem
A retail business generating ₹438K in revenue needs to understand why certain months (like May and August) show significant profit dips despite stable sales volume.

🎯 Dashboard Goals
Revenue Tracking: Monitor the ₹438K total revenue and ₹37K net profit in real-time.

Geospatial Analysis: Identify Madhya Pradesh and Maharashtra as the primary revenue drivers.

Category Optimization: Analyze why Clothing dominates volume (63%) while Printers drive the highest sub-category profit.

🔍 Walkthrough of Key Visuals
Executive KPI Header: Displays Total Revenue (₹438K), Net Profit (₹37K), Avg. Transaction Value (₹121.01), and Total Units Sold (5,615).

Monthly Profitability Trend (Bar/Line): Highlights seasonal volatility, specifically identifying the recovery period in November (₹10K+ Profit).

Category Volume (Donut Chart): Breaks down sales by Clothing (63%), Electronics (21%), and Furniture (17%).

Customer Leaderboard: Identifies top-tier customers like Harivansh and Madhav to support loyalty program targeting.

Sub-Category Margin Analysis: A horizontal bar chart revealing that Printers and Bookcases are the most lucrative segments.

📈 Business Impact
Loss Mitigation: By identifying loss-making months (May, July, August), management can investigate seasonal supply chain costs or discount fatigue.

Regional Strategy: Data proves that focus should remain on the Central and Western regions (MP & Maharashtra) for expansion.

Inventory Efficiency: Highlighting that Tables are a low-profit sub-category suggests a need for price restructuring or supplier renegotiation.

6. Screenshot / Demos

   A high-fidelity snapshot of the final executive interface, featuring real-time KPI tracking and multi-dimensional filtering across Indian states.

   Dashboard preview (https://github.com/mihirmpatwardhan/Retail-Performance-Profitability-Intelligence-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)

   
   
