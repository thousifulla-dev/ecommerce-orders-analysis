# E-Commerce Orders Analysis

## Objective
Clean and analyze e-commerce transaction data to find 
key insights about products, customers, and revenue trends.

## Tools Used
- Python (Pandas, NumPy)
- SQL (sqlite3 inside Colab)
- Google Colab

## Dataset
UCI E-Commerce Dataset from Kaggle — 200k+ transactions

## Business Questions Answered
1. Top 10 best selling products by revenue
2. Top 10 countries by total revenue
3. Monthly revenue trend
4. Top 10 customers by total spending
5. Average order value per country
6. Country revenue ranking using Window Functions

## Key Findings

- Top selling product by revenue was "REGENCY CAKESTAND 3 TIER" 
  indicating strong demand for home and kitchen products


- United Kingdom dominated revenue with ₹2,778,328 — accounting 
  for approximately 81% of total global revenue


- May 2011 recorded the highest monthly revenue of ₹678,594 
  with 1,555 orders. Note: dataset appears incomplete after 
  June 2011 — full year trend may differ


- Top customer (ID: 14646) spent ₹116,135 - significantly higher 
  than the average customer spend, indicating a high-value B2B buyer


- Netherlands led all countries with the highest average order 
  value of ₹123.91 across 38 orders, followed by Australia 
  (₹115.06) and Sweden (₹97.96) — suggesting these markets 
  consist primarily of wholesale or B2B buyers placing 
  high-value orders, unlike UK which has high volume 
  but lower average order size
  

- Window function analysis confirmed UK, Netherlands and EIRE 
  consistently rank in top 3 by revenue across all periods
