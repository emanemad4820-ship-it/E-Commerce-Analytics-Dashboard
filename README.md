# E-Commerce Analytics Dashboard

An 8-page Power BI dashboard analyzing the **Olist Brazilian E-Commerce** public dataset — connecting customers, orders, sellers, products, payments, and reviews into a single data model to surface revenue, delivery, and satisfaction insights.

## 📊 Overview

- **99,441** orders analyzed
- **$13.59M** in total revenue
- **103,883** payment transactions processed
- Data model built across 6+ relational tables (customers, orders, order items, payments, reviews, products, sellers)

## 🔍 Key Insights

**Delivery Performance**
- Average actual delivery time: **12.5 days**, well under the 24.4-day estimate given to customers — suggesting delivery estimates are set conservatively.
- Late-delivery rate: **7.87%** (about 8K of 97K tracked orders arrived late).
- Review scores dropped sharply on late orders — from **4.29** average down to **2.57** — making delivery speed the clearest driver of customer satisfaction.

**Payments**
- 103,883 transactions, averaging **$154.10** each.
- Credit card is the dominant payment method (**73.5%** of volume), followed by boleto (19%).

**Sellers & Geography**
- São Paulo dominates the seller base — roughly **60% of all sellers** — and generated **$8.8M** of the $13.59M total revenue, while also carrying the lowest average shipping cost of any state.
- Nearly **86%** of sellers (2,635 of 3,095 reviewed) shipped fewer than 50 orders each, together contributing only **22.3%** of total order volume — showing a long tail of small sellers alongside a concentrated top segment.

**Products**
- **Beauty & Health** and **Watches & Gifts** were the top-performing categories, each surpassing **$1.2M** in revenue.

## 🗂️ Dashboard Pages

| Page | Description |
|---|---|
| Home | Landing/navigation page |
| Overview | High-level KPIs — revenue, orders, delivery, growth trend |
| Customer | Customer-level behavior and payment patterns |
| Seller Performance | Seller-level revenue, order volume, and shipping cost |
| States | Geographic breakdown of orders, revenue, and delivery |
| Report | Written summary of insights (see above) |
| Why product *(drillthrough)* | Category-level deep dive |
| Map *(tooltip)* | State-level map tooltip detail |

## 🛠️ Tools & Techniques

- **Power BI** — report design, data modeling, drillthrough & tooltip pages
- **DAX** — custom measures (Revenue, Freight-to-Price Ratio, Late Orders Count, average delivery/shipping days)
- **Power Query** — data cleaning and transformation across multiple source tables

## 📁 Files

- `E-Commerce.pbix` — full Power BI report file
- `screenshots/` — page exports for quick preview without opening Power BI

## 📌 Dataset

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — real, anonymized order data from a Brazilian e-commerce marketplace.

---
**Author:** Eman Emad Eldin — Data Analyst
[LinkedIn](https://www.linkedin.com/in/eman-emad-eldin-68890529a) | [GitHub](https://github.com/emanemad4820-ship-it)
