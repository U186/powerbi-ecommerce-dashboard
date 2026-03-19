# 📊 Power BI Project – E-Commerce Sales & Customer Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-E--Commerce%20Analytics-blue?style=flat-square)
![Pages](https://img.shields.io/badge/Dashboard%20Pages-5-orange?style=flat-square)

## 📌 Project Overview

This project is a **5-page interactive Power BI dashboard** built on the same E-Commerce dataset used in my SQL analysis project. The goal was to go beyond SQL queries and turn raw data into **visual, business-ready insights** that a non-technical stakeholder could immediately understand and act on.

> 💡 This dashboard complements the [SQL E-Commerce Analysis](https://github.com/U186/sql-ecommerce-analysis) project — the SQL project extracts insights through queries; this dashboard presents them visually with interactive filters.

---

## 🗂️ Dataset

| Field | Detail |
|---|---|
| **Records** | 50,000+ transactions |
| **Key Metrics** | Total Revenue: 339M \| Total Customers: 25K \| Total Orders: 124K \| Avg Order Value: 2.72K |
| **Categories** | Books, Clothing, Electronics, Home |
| **Payment Methods** | Credit Card, PayPal, Cash, Crypto |

---

## 📄 Dashboard Pages

### Page 1 — Executive KPI Overview
**Business Question:** What is the overall health of the business?

- KPI cards: Total Revenue (339M), Total Customers (25K), Total Orders (124K), Average Order Value (2.72K)
- Revenue trend line by month — identifies seasonal peaks and drops
- Revenue by Product Category (bar chart)
- Revenue by Payment Method (donut chart) — Credit Card leads at 40.19%
- **Interactive Gender filter** — slice all visuals by Male/Female

---

### Page 2 — Product Category Deep Dive
**Business Question:** Which product categories are driving revenue, volume, and returns?

- Revenue by Product Category — Books and Clothing lead
- Quantity sold by Product Category — Clothing highest in volume
- Average Order Value by Category — consistent ~2.7K across all categories
- Returns by Product Category — Books and Clothing also have highest returns
- **Interactive Product Category slicer**

---

### Page 3 — Customer Segmentation
**Business Question:** Who are our most valuable customers and how do demographics affect spending?

- Revenue by Gender — nearly equal split (Female 50.26% vs Male 49.74%)
- Revenue by Age Group — 46+ segment contributes the most revenue (~0.3bn)
- Total Revenue by Age Group and Gender — clustered bar for cross-analysis
- Top 10 customers by revenue table — John Smith leads at 286,353
- Revenue by Payment Method — Credit Card dominates at 40.24%

---

### Page 4 — Churn Analysis
**Business Question:** How much revenue are we losing to churned customers and which segments churn most?

- Active vs Churned customer count — ~40K active vs ~10K churned
- Revenue by Churn Status — active customers generate ~5x more revenue
- Churn by Product Category — Clothing and Books have highest churn counts
- Churn by Age Group — 46+ segment has the most churned customers in absolute numbers
- **Actionable Insight:** Retention campaigns should focus on Clothing/Books buyers in the 46+ segment

---

### Page 5 — Returns Analysis
**Business Question:** Where are returns concentrated and what drives return behaviour?

- Total Returns: 101K
- Returns by Age Group — evenly distributed across all age segments
- Returns by Payment Method — uniform across Credit Card, PayPal, Cash, Crypto
- Returns by Product Category — Books and Clothing lead in return volume

---

## 🧠 Key Business Insights

| # | Insight | Business Recommendation |
|---|---|---|
| 1 | Credit Card is used in 40%+ of all transactions | Offer Credit Card-exclusive discounts to increase AOV |
| 2 | 46+ age group generates the most revenue | Target premium products and loyalty programs at this segment |
| 3 | Churned customers = ~20% of customer base | Launch re-engagement email campaigns for churned segment |
| 4 | Books & Clothing have highest returns | Investigate product quality/description accuracy for these categories |
| 5 | Revenue split is almost equal between genders | Marketing campaigns don't need heavy gender segmentation |
| 6 | Revenue dips sharply after June | Plan promotional campaigns for Q3 to counter the mid-year slump |

---

## 🛠️ Tools & Features Used

| Feature | Used |
|---|---|
| KPI Cards | ✅ |
| Line Charts (Trend) | ✅ |
| Bar & Clustered Bar Charts | ✅ |
| Donut / Pie Charts | ✅ |
| Interactive Slicers (Gender, Category) | ✅ |
| Data Tables | ✅ |
| Multi-page Report | ✅ (5 pages) |
| Cross-visual Filtering | ✅ |

---

## 📁 File Structure

```
powerbi-ecommerce-dashboard/
│
├── README.md
├── dashboard_screenshots/
│   ├── page1_kpi_overview.png
│   ├── page2_product_category.png
│   ├── page3_customer_segmentation.png
│   ├── page4_churn_analysis.png
│   └── page5_returns_analysis.png
└── power_bi_project.pdf        ← Full dashboard export
```

---

## 🔗 Related Project

This dashboard is built on the same dataset as my SQL project:
👉 [SQL E-Commerce Customer Data Analysis](https://github.com/U186/sql-ecommerce-analysis)

Together they demonstrate the **full analytics workflow**: SQL for data extraction and insight generation → Power BI for visual storytelling and business reporting.

---

## 👨‍💻 Author

**Ujjwal Jain**  
B.Sc. E-Commerce Operations & Digital Applications — DSEU, Delhi  
📧 ujjwalj35@gmail.com | [LinkedIn](https://www.linkedin.com/in/ujjwal-jain-37146b303)
