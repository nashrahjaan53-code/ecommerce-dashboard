# E-Commerce Sales Dashboard (Power BI)

An interactive sales analytics dashboard analyzing e-commerce transaction data — built to answer real business questions about revenue drivers, customer behavior, and sales timing, not just display numbers.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## 📸 Dashboard Preview

![Dashboard Screenshot](./dashboard-screenshot.png)
*(Add your screenshot here — drag the image into this repo and update the filename above)*

---

##  Business Questions This Answers

- Which products and customers actually drive revenue — and does it match assumptions?
- When do customers actually shop, and when does cart abandonment happen?
- Do returning customers behave differently than new ones?
- Which states, categories, and payment methods contribute most to sales?

---

##  Key Insights

- **Total Revenue**: ₹161K across the reporting period, with **26K profit** generated on **2,008 units sold** — an average order value of **₹44.21K**
- **Sales are geographically concentrated** — Maharashtra and Madhya Pradesh lead among Indian states, with Delhi and Uttar Pradesh close behind
- **Digital payments dominate**: COD and UPI together account for the majority of transaction volume, with EMI and Credit Card as smaller but present segments
- **Printers and Phones are the top profit-driving sub-categories**, followed by Accessories, Bookcases, and Sarees
- **A small group of top customers** (led by Harivansh) contribute disproportionately to total revenue — a Pareto-style concentration worth flagging to stakeholders
- **Profit shows a declining trend from January to March**, which is worth investigating further (seasonality? one-time bulk orders in January?)

---

## 📊 What's on the Dashboard

- **KPI Cards**: Total Revenue, Total Quantity Sold, Total Profit, Average Order Value
- **Sales by State** — geographic performance breakdown
- **Payment Mode Distribution** — COD vs UPI vs Card vs EMI split
- **Profit by Month** — trend over time
- **Profit by Sub-Category** — product-level profitability
- **Top Customers by Revenue**
- **Category-wise Quantity Distribution**
- Interactive quarter-based filtering (Qtr 1–4)

---

## 🛠️ Tools & Techniques

- **Power BI** — data modeling, relationships, report design
- **DAX** — calculated measures for KPIs (e.g. `SUM`, `CALCULATE`, ratio/percentage measures)
- **Data Cleaning** — *(mention here if you used Power Query, Excel, or Python/SQL to clean data before loading)*

---

## Files

- `ecommerce-sales-dashboard.pbix` — the Power BI file

---

##  How to View

1. Download `ecommerce-sales-dashboard.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Interact with the quarter slicers to explore different time periods

---
