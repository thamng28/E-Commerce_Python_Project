📌 Project Overview

This project analyzes a transactional dataset from a UK-based online retail company to uncover actionable business insights. The analysis focuses on three core areas: Sales & Revenue Trends, Product & Inventory Performance, and Customer Behavior Analysis.

The goal of this project is to provide data-driven recommendations to optimize inventory, increase Customer Lifetime Value (CLV), and improve targeted marketing strategies.

🛠️ Tools & Technologies Used

Python (Data Cleaning, Transformation, and Analysis)

Pandas (Data Manipulation & Time-Series Parsing)

Matplotlib / Seaborn (Data Visualization)

Jupyter Notebook / Visual Studio (IDE)

🗂️ Data Source

The dataset used is the online_retail.csv dataset, which contains transactional records of wholesale and retail purchases occurring over a 12-month period.

📊 Key Business Questions Answered

Part I: Sales & Revenue Trends

What are the weekly, monthly, and quarterly profit and revenue trends for UK customers?

How do order sizes and values compare between domestic (UK) and international customers?

Which top 5 international markets generate the highest total revenue?

Part II: Product & Inventory Performance
4. Which top 10 products drive the highest revenue and volume?
5. Which specific products suffer from the highest cancellation or return rates?
6. Market Basket Analysis: Which products are frequently bought together?

Part III: Customer Behavior Analysis
7. Who are the top 10% highest-spending customers, and what is their revenue impact?
8. What is the purchase frequency of unique customers, and how can we increase CLV?
9. How much revenue is driven by first-time buyers versus repeat customers?

💡 Key Insights & Strategic Recommendations

1. Capitalize on Customer Concentration

Insight: Customer revenue is highly skewed. The top 10% of spenders generate 61% of total revenue (4.5x higher than the second-highest tier). Furthermore, repeat customers overwhelmingly drive monthly volume.

Recommendation: Launch a VIP Retention Program offering personalized rewards and early access. Utilize Lookalike Modeling based on this top 10% to acquire high-LTV (Lifetime Value) customers rather than just driving high-volume, low-converting traffic.

2. Optimize Inventory & Merchandising

Insight: Top product performance is volume-driven. Core items like the Jumbo Bag Red Retrospot and Rabbit Night Light are massive hits. Market basket analysis shows customers frequently buy complementary items (e.g., Green and Pink Regency Teacups).

Recommendation: Leverage "Frequently Bought Together" bundles for website upselling and targeted email campaigns. Physically group frequently paired items in the warehouse to speed up order fulfillment.

3. Streamline Geographic & Seasonal Focus

Insight: The business relies heavily on the Q4 holiday season (Oct–Dec). Geographically, the UK is the primary engine, driving 67% of order volume and 71% of total revenue.

Recommendation: Secure the supply chain for the top 5 MVP products well ahead of the Q4 surge. Focus international marketing spend strictly on proven top-tier markets (Netherlands, EIRE, Germany, Australia) rather than lower-performing regions.
