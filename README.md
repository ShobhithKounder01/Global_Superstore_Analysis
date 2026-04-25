# Global Superstore SQL Analysis

## 📊 Project Overview
Comprehensive SQL analysis on the **Global Superstore dataset** (51,290 orders from 2011–2014 across 7 global markets).  
Explored sales, profit, customer segments, product performance, shipping, discounts, and loss-making areas using MySQL.

**Dataset:** Kaggle Global Superstore  
**Tools:** MySQL (Queries, CTEs, Window Functions)

## 🛠️ Skills Demonstrated
- Data loading and date cleaning
- Exploratory Data Analysis (EDA)
- Business performance metrics (Sales, Profit, Margin)
- Market, Category, Customer & Discount analysis
- Advanced SQL: Window functions, CTEs, Ranking

## 📁 Project Structure
- `superstore_analysis.sql` — Complete SQL script with all queries
- `outputs/` — Exported results of key queries (CSV)

## 🔑 Key Insights
- Tables sub-category incurs losses due to high discounts
- Discounts > 20% consistently lead to losses across categories
- APAC leads in sales; Canada has the highest profit margin (~26.62%)
- Top 10% of customers contribute ~26% of total profit
- Technology (Copiers) is highly profitable; Furniture needs improvement

## How to Run the Project
1. Create database `superstore_db`
2. Import the CSV file using Table Data Import Wizard or LOAD DATA
3. Open Queries.sql file COPY And PASTE it in your workspace OR
4. Run the `superstore_analysis.sql` script

## Future Plans
- Excel analysis on the same dataset
- Power BI dashboard for interactive visualizations

⭐ If this project helped you, feel free to star the repo!
