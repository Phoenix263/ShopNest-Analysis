# 🛍️ ShopNest Store — Business Analytics Dashboard (Power BI)

> An end-to-end business analytics dashboard built in **Power BI** using 9 connected e-commerce datasets — covering sales, deliveries, payments, ratings, and regional performance.

## 📌 Business Problem

ShopNest is an e-commerce store with data spread across multiple datasets. As an analyst, the goal was to bring it all together and answer one central question:

**How is the business actually performing — and where can it improve?**

Without a unified view, it's impossible to know which categories are driving revenue, whether deliveries are meeting customer expectations, or which regions are underperforming. This dashboard gives decision-makers a single place to track all of it.


## 🗂️ Dataset Overview

The dashboard was built by connecting **9 e-commerce datasets** in Power BI, covering:

| Data Area | What It Covers |
|---|---|
| 🛒 Orders | Order IDs, dates, delivery status |
| 📦 Products | Categories, product details |
| 💳 Payments | Payment method per transaction |
| ⭐ Reviews | Customer ratings per product |
| 📍 Customers | Location/state information |
| 📅 Dates | Time intelligence for trends |

## 🔧 Process

- Connected and related all 9 datasets in Power BI's data model
- Created calculated columns and DAX measures (e.g. delayed order flags, revenue totals, average ratings)
- Built **KPI cards** for top-level metrics and **slicers** for interactivity
- Enabled **drillthrough cross-report** functionality for deep-dive delivery analysis


## 📊 Business Questions Answered

### `Q1` 🏆 Top Categories by Total Sales
**Which product categories are generating the most revenue?**  
A clustered bar chart ranks the top 10 categories by total sales. **Health & Beauty** leads, followed by **Watches & Gifts** and **Bed, Bath & Table** — these are the priority categories for stock planning and marketing spend.

##
### `Q2` 🚚 Delayed Orders by Category
**Where are delivery problems concentrated?**  
Orders were flagged as delayed when the actual delivery date exceeded the estimated date. Categories like **Bed Bath Table**, **Health Beauty**, and **Sports Leisure** showed the highest delay counts — pointing to where logistics improvements are most needed.

##
### `Q3` 📅 Monthly Delayed vs On-Time Orders
**Is delivery performance improving or getting worse over time?**  
A clustered column chart compares delayed and on-time orders month by month. On-time orders generally outpace delays, but certain months show noticeable spikes — useful for identifying seasonal pressure points. Drillthrough enabled for detailed monthly breakdowns.

##
### `Q4` 💳 Payment Method Breakdown
**How do customers prefer to pay?**  
A donut chart breaks down transactions by payment type. **Credit card** dominates, with **Boleto** as a distant second. This shapes decisions around checkout experience and payment gateway prioritisation.

##
### `Q5` ⭐ Top & Bottom Rated Products
**What are customers loving — and complaining about?**  
Two bar charts show the top 10 highest-rated and bottom 10 lowest-rated products based on review scores. High-rated products score close to **5.00**; low-rated products hover around **1.00** — flagging items that need quality checks or seller review.

##
### `Q6` 🗺️ State-wise Sales Performance
**Which regions are driving sales, and which are lagging?**  
A bar chart ranks all states by total sales. **SP (São Paulo)** dominates by a large margin, followed by **RJ** and **MG** — indicating where demand is strongest and where there's room for regional expansion or targeted campaigns.

##
### `Q7` 📈 Seasonal Sales Patterns
**Are there quarters where sales consistently spike or drop?**  
A line chart plots quarterly sales trends. Sales were stronger in later periods and lower in early quarters — helping ShopNest time promotions, inventory builds, and campaign launches around demand peaks.

##
### `Q8` 💰 Yearly Revenue Analysis
**How has total revenue grown over time?**  
A KPI card shows overall revenue of approximately **₹13.59M**, while a column chart breaks it down by year. Revenue grew significantly from 2016 → 2017 → 2018, confirming strong year-on-year business growth.


## 💡 Key Takeaways

- 🏆 Health & Beauty and Watches & Gifts are the top revenue-driving categories — worth protecting with strong stock and promotions
- 🚚 Delayed deliveries are concentrated in specific categories — a targeted logistics fix could meaningfully improve customer satisfaction
- 💳 Credit card is the dominant payment method — optimising that flow has the highest customer impact
- 🗺️ Sales are heavily skewed toward SP — significant untapped opportunity in other states
- 📈 Revenue has grown consistently year-on-year, validating the business trajectory


## 🛠️ Tools Used

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)


---

*🙋 Built as part of a personal data analytics portfolio. Dataset based on a simulated e-commerce store.*
