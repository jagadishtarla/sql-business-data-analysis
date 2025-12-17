# SQL Business Data Analysis – Online Retail Dataset

This project analyzes real-world transactional data from a UK-based online retail company
to extract business insights using SQL and Python.

The goal of the analysis is to understand revenue performance, customer behavior,
and lifetime value using a normalized relational data model.

---

## Dataset
**Online Retail II Dataset** (Kaggle)

- Time period: Dec 2009 – Dec 2011
- Business type: Online retail selling gift-ware
- Customer base: Includes a significant number of wholesale customers

---

## Tools & Technologies
- Python (Pandas, SQLite)
- SQL (Joins, Aggregations, Subqueries)
- Jupyter Notebook
- Matplotlib (basic visualizations)

---

## Data Preparation
- Combined multiple Excel sheets into a single dataset
- Removed cancelled invoices and invalid transactions
- Filtered out records without customer identifiers
- Normalized raw transactional data into:
  - customers
  - products
  - orders
  - order_items

---

## Key Business Insights

### Revenue Overview
- Total revenue: **£17.7M**
- Average order value: **£481**
- Revenue is heavily concentrated in the UK market

### Customer Behavior
- ~72% of customers are repeat buyers
- Order frequency and revenue patterns indicate wholesale purchasing behavior

### Customer Lifetime Value (CLV)
- Average CLV: **£3,025**
- Median CLV: **£900**
- CLV distribution is highly skewed, with a small number of customers
  contributing a large share of total revenue

---

## Conclusion
The analysis confirms that the business is driven primarily by a small group of
high-value, repeat wholesale customers. These insights can support decisions
around customer retention, pricing strategy, and international expansion.

---

## Files
- `sql_online_retail_analysis.ipynb` – End-to-end analysis
- `dataset/online_retail_II.xlsx` – Raw dataset
