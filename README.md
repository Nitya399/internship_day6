# 📊 Sales Trend Analysis using SQL – Day 6 Task

This project focuses on analyzing monthly sales trends using the **Olist Ecommerce Public Dataset**. It uses SQL (MySQL) to extract and aggregate order and payment data, helping derive insights such as revenue trends and order volumes over time.

---

## 🚀 Objective

To perform sales trend analysis by calculating:
- Total revenue (sum of payments)
- Total number of orders per month
- Monthly breakdown for better decision-making

---

## 🧰 Tools Used

- **Database:** MySQL
- **Language:** SQL
- **Dataset:** [Olist Ecommerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
  *(Used: `olist_orders_dataset.csv`, `olist_order_payments_dataset.csv`)*

---

## 📂 Dataset Description

| File                         | Description                                  |
|-----------------------------|----------------------------------------------|
| `olist_orders_dataset.csv`  | Contains order IDs, customer IDs, and dates  |
| `olist_order_payments_dataset.csv` | Contains order IDs and payment details    |


...	...	...
🧠 Key Learnings
✅ How to extract month and year using DATE_FORMAT

✅ How to join datasets using common keys

✅ How to aggregate using SUM() and COUNT()

✅ Grouping and ordering data for time-series analysis

💡 Insights
Peak order volume was observed in [Month, Year]

Revenue was consistently higher during the holiday season (e.g. November-December)

Card payments dominated the payment method choice

🏁 Conclusion
Using just two datasets and simple SQL techniques, I was able to extract business-critical metrics like revenue growth, sales volume, and time-based trends. This project sharpened my SQL aggregation, join, and data grouping skills in a real-world scenario.
