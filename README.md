# FUTURE_DS_01 — Business Sales Performance Analytics

**Internship:** Future Interns — Data Science & Analytics Track
**Task:** 1 of 3

## 📌 Objective
Analyze business sales data to identify revenue trends, top-selling products, high-value categories, and regional performance — and turn those findings into a client-ready set of insights and recommendations.

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Project Structure
```
FUTURE_DS_01/
├── data/
│   └── sales_data.csv                 # Sales transaction dataset
├── notebook/
│   └── Task1_Sales_Performance_Analysis.ipynb
├── outputs/
│   ├── monthly_revenue_trend.png
│   ├── top_products.png
│   ├── category_revenue.png
│   ├── regional_revenue.png
│   ├── segment_revenue.png
│   └── payment_methods.png
├── requirements.txt
└── README.md
```

## 📊 Dataset
`data/sales_data.csv` contains ~6,000 order-level records with the following fields:

| Column | Description |
|---|---|
| OrderID | Unique order identifier |
| OrderDate | Date the order was placed |
| CustomerID | Unique customer identifier |
| CustomerSegment | New / Returning / VIP |
| Region | Sales region (North, South, East, West, Central) |
| Category | Product category |
| Product | Product name |
| UnitPrice | Price per unit |
| Quantity | Units sold |
| DiscountPct | Discount applied (%) |
| GrossRevenue | Revenue before discount |
| DiscountAmount | Discount value |
| NetRevenue | Final revenue after discount |
| PaymentMethod | Payment method used |
| IsReturned | Whether the order was returned |

> **Note:** This is a synthetically generated but realistic dataset built to mirror real-world e-commerce sales data, including intentional data-quality issues (missing values, inconsistent casing, invalid entries, duplicates) that are cleaned within the notebook. If you have your own real sales dataset, simply replace `data/sales_data.csv` with the same column structure — the notebook will run without any code changes as long as column names match.

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook/Task1_Sales_Performance_Analysis.ipynb
```
Then run all cells (Kernel → Restart & Run All).

## 🔍 Key Insights
1. Revenue peaks strongly in November–December, driven by seasonal demand.
2. Electronics and Home & Kitchen are the top revenue-generating categories.
3. Revenue performance varies meaningfully by region, highlighting growth opportunity in underperforming areas.
4. VIP customers contribute disproportionately high average order value despite being the smallest segment.
5. Credit Card and UPI are the dominant payment methods.

## ✅ Recommendations
- Prepare inventory and marketing ahead of the Nov–Dec peak season.
- Prioritize investment in top-performing categories.
- Run targeted regional campaigns to close performance gaps.
- Build a loyalty/VIP program to increase high-value customer retention.
- Streamline checkout for the most-used payment methods.

---
*Submitted as part of the Future Interns Data Science & Analytics Internship.*
