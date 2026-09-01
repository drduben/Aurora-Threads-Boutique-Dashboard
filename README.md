# Aurora-Threads-Boutique-Dashboard
Case study built for Aurora Threads Boutique, a high-end fashion retailer, to demonstrate how DAX and Power Query M can turn raw multi-store sales data into a live, interactive performance dashboard for business decision-making.
🎯 The Business Problem

Aurora Threads was struggling to turn its growing volume of sales data into actionable insight. Specifically, the boutique lacked visibility into:

Product trends — which categories and individual products were actually driving revenue
Performance tracking — inefficient, manual tracking made it hard to compare store and product performance over time
Advanced analytics capability — without dynamic calculations, the business couldn't answer timely questions about sales, customers, or trends

The brief called for a Power BI solution built around DAX (for dynamic calculations and measures) and Power Query M (for data transformation), designed to answer a specific set of business questions for leadership.

🛠️ Methodology: DAX & Power Query (M)

The dashboard was built using Power BI's two core engines:

Power Query (M language) was used on the data-preparation layer — importing and shaping the raw sales, product, customer, and store tables, standardizing data types (dates, currency, categorical fields), and merging/relating tables into a clean data model ready for analysis.
DAX (Data Analysis Expressions) was used to build the dynamic measures powering every visual on the dashboard, including:
Total Revenue and Total Quantity Sold — aggregate SUM measures
Average Revenue — an AVERAGE/DIVIDE-based measure summarizing daily revenue performance
Total Customers and Number of Stores — DISTINCTCOUNT measures over the customer and store dimensions
% of total calculations (e.g., revenue share by gender and payment type) using CALCULATE and ALL/ALLSELECTED to compute proportions dynamically as filters change
Store slicers (Store A / B / C, top right of the dashboard) allow the report to be filtered interactively without touching the underlying measures — a core benefit of the DAX-driven approach.
📊 The Dashboard
Headline KPIs
Metric	Value
Total Quantity Sold	771 units
Total Revenue	$288K
Number of Stores	3
Total Customers	31
Average Daily Revenue	$3.10K
Visuals included
Revenue by Product Category (bar chart) — Accessories, Clothing, Footwear
Revenue by Product (bar chart) — top 10 individual products by revenue
Revenue by Gender (donut chart) — Male, Female, Unisex revenue share
Revenue by Payment Type (pie chart) — Cash, Credit Card, Online Pay, Debit Card
Revenue by Day (line chart) — daily revenue trend across the reporting period
Customer Revenue Table — customer-level revenue and quantity purchased, sortable
Store filter/slicer — Store A, B, C for interactive drill-down
✅ Business Questions — Answered
Business Question	Answer
Top-selling product category	Accessories — $148K, ~51% of total revenue, more than double the next category
Top 10 products by revenue	Handbag leads at $24K, followed by Necklace ($22K), Sunglasses & Wallet ($19K each), Boots & Loafers ($18K each), Sandals ($17K), Ring ($15K), and Jumpsuit & Watch ($12K each)
Sales trend over time	Revenue is highly volatile day-to-day, swinging between roughly $2K and $24K, with an overall average of $3.10K/day and no single sustained upward or downward trend — indicating spiky, event- or promotion-driven demand rather than steady organic growth
Gender-based sales distribution	Unisex products drive the most revenue ($121K, 42%), ahead of Female ($102K, 35%) and Male ($65K, 23%)
Most popular payment types	Cash is the leading payment method (31%), closely followed by Online Pay (30%) and Credit Card (25%); Debit Card trails at 14%
Customer revenue & quantity list	Delivered as an interactive table; e.g. top customer CUST026 generated $21,600 in revenue from 36 units purchased, while CUST029 and CUST030 each contributed $15,000 and $14,520 respectively
🔍 Key Insights
Accessories is the core growth engine: at $148K, Accessories alone generates more revenue than Clothing and Footwear combined — a strong signal for inventory and marketing prioritization.
The Handbag is the single best-performing SKU in the store, generating $24K — worth protecting stock levels and considering for cross-sell bundles with lower-performing accessories.
Unisex framing outperforms gendered marketing: Unisex product revenue (42%) exceeds both Female and Male categories individually, suggesting Aurora Threads' unisex lines resonate strongly and may warrant expanded assortment.
Cash and digital payments are roughly balanced, with Cash only marginally ahead of Online Pay — a sign the boutique should continue supporting both physical and digital checkout experiences equally rather than favoring one.
Daily revenue is highly volatile, not steadily trending — this points to promotional spikes, weekend/event-driven traffic, or inconsistent footfall rather than predictable organic growth, and is worth investigating against a marketing/promotions calendar.
Customer revenue is concentrated among a small group of high-value shoppers (e.g., CUST026 at $21,600) — a strong candidate list for a VIP/loyalty program targeting the boutique's 31 total customers.
💡 Recommendations
Double down on Accessories and top SKUs like the Handbag and Necklace — expand assortment depth and ensure consistent stock availability.
Expand the Unisex product line, given it already outperforms gender-specific categories in revenue share.
Investigate the drivers behind daily revenue spikes (promotions, events, paydays) to replicate high-performing days more consistently.
Launch a loyalty/VIP tier for top customers identified in the customer revenue table to protect and grow high-value relationships.
Maintain multi-channel payment support, since no single payment method dominates — Cash, Online Pay, and Credit Card are all meaningfully used.
🛠️ Skills Demonstrated

Power BI · DAX Measures · Power Query (M Language) · Data Modeling · Interactive Dashboard Design · Retail Analytics · KPI Development · Business Insight Generation

📁 Repository Contents
Aurora_Threads_Botiques_Dashboard.png — dashboard screenshot
Aurora Threads Boutique Case Study brief.docx — original project brief
README.md — this write-up

Case study based on the Aurora Threads Boutique project brief. #PowerBI #DataAnalytics #RetailAnalytics
