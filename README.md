# 📱 Mobile Sales Analysis Dashboard | Power BI

> **Interactive business intelligence dashboard for mobile sales performance, product trends, customer ratings, payment behavior, geography, and time-based analysis.**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-1F4E79?style=flat-square)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-217346?style=flat-square)
![Status](https://img.shields.io/badge/Project-Completed-success?style=flat-square)

## 📊 Project Overview

This project is an interactive **Mobile Sales Analysis Dashboard** developed entirely in **Microsoft Power BI**. The report converts mobile transaction data into a management-friendly reporting interface so users can explore sales performance from multiple business perspectives.

The dashboard combines **KPI monitoring, time intelligence, product analysis, city-level analysis, customer ratings, payment methods, and interactive slicers** in a single reporting solution.

---

## 🎯 Business Objective

The goal was to build a reporting solution that helps a business quickly answer questions such as:

- What is the overall sales and transaction performance?
- How are sales changing across years, quarters, months, and days?
- How does the current period compare with the same period last year?
- Which mobile models are contributing the most sales?
- Which cities generate stronger sales?
- What payment methods are customers using?
- What is the distribution of customer rating status?
- How does performance change when users filter by model, brand, payment method, or time?

**Business flow:** `Transaction Data → Data Preparation → DAX Analysis → Interactive Dashboard → Business Insights`

---

## 🖼️ Dashboard Preview

### 1. Mobile Sales Overview

![Mobile Sales Dashboard Overview](./Screenshot%202026-06-23%20135029.png)

This page provides an executive-style overview with KPI cards, city-level sales, monthly quantity trends, rating status, payment-method distribution, mobile-model performance, and day-wise sales.

### 2. MTD / Period Analysis

![MTD Report](./Screenshot%202026-06-23%20135106.png)

The period-analysis page focuses on comparing sales performance across time and supporting management-style period reporting.

### 3. Same Period Last Year Analysis

![Same Period Last Year Analysis](./Screenshot%202026-06-23%20135318.png)

This page provides year-, quarter-, and month-level comparison between **Total Sales** and **Same Period Last Year**, supporting trend and performance evaluation.

---

## 📌 Dashboard KPIs

In the default dashboard view shown in the project screenshots, the headline KPIs include:

| KPI | Dashboard Value |
|---|---:|
| **Total Sales** | ₹769.20M |
| **Total Quantity** | 19K |
| **Average Price** | ₹40K |
| **Transaction Count** | 3.835K |

> KPI values are filter-responsive and can change when slicers are applied.

---

## 🔎 Analysis Covered

### 📈 Sales Performance

- Total sales monitoring
- Year-wise sales comparison
- Quarter-wise performance
- Month-wise performance
- Current period vs. same period last year
- Day-wise sales analysis

### 📱 Product Performance

- Mobile model-wise sales
- Quantity trends by month
- Identification of higher-contributing mobile models
- Brand and model filtering

### 🌍 Geographic Performance

- City-wise sales visualization using a map
- Geographic comparison of transaction performance

### 💳 Payment Analysis

The dashboard compares transactions across:

- UPI
- Debit Card
- Credit Card
- Cash

### ⭐ Customer Rating Analysis

Customer ratings are grouped into:

- Good
- Average
- Poor

This allows the report user to understand the overall distribution of customer feedback.

### 🗓️ Time Intelligence

The report supports analysis across:

- Year
- Quarter
- Month
- Day
- Same Period Last Year

---

## 💡 Business Insights Visible in the Dashboard

The dashboard's default view highlights several useful observations:

- Total sales are approximately **₹769.2M** across the displayed data.
- The year-wise visual shows a strong increase from 2021 to 2022, followed by comparatively high sales in 2023 and a lower total in 2024 in the displayed period.
- The same-period comparison makes it possible to identify periods where current sales are ahead of or behind the prior-year benchmark.
- In the displayed mobile-model visual, **iPhone SE (~₹60M)** is among the strongest contributors, followed by models such as **OnePlus Nord (~₹58M)** and a **Galaxy Note model (~₹56M)**.
- Payment activity is relatively distributed across UPI, debit card, credit card, and cash rather than being dominated by a single method.
- The monthly quantity trend shows noticeable variation, with **July** appearing as one of the stronger months in the displayed view and **February** among the lower points.
- City-level mapping allows management to identify geographic differences in sales performance.

> These observations describe the dashboard's displayed/default view; slicer selections can change the results.

---

## 🎛️ Interactive Features

The dashboard allows users to slice and investigate the data through controls such as:

- **Mobile Model**
- **Brand**
- **Payment Method**
- **Year / Quarter / Month / Day**
- **Month navigation**

The combination of slicers and cross-filtering makes the report suitable for interactive management reporting rather than a static presentation.

---

## 🛠️ Tools & Technical Skills

| Technology / Skill | Application in Project |
|---|---|
| **Microsoft Power BI** | Dashboard development and reporting |
| **Power Query** | Data preparation and transformation |
| **DAX** | KPIs, calculations and time-based analysis |
| **Data Modeling** | Structuring data for interactive analysis |
| **Data Visualization** | KPI cards, charts, tables, map and donut chart |
| **Business Analysis** | Converting transaction data into decision-oriented views |

---

## 🧠 Skills Demonstrated

- Data Analysis
- Business Intelligence
- Power BI Dashboard Development
- DAX & Time Intelligence
- Power Query / Data Transformation
- KPI Development
- Data Visualization
- Interactive Reporting
- Trend Analysis
- Comparative Analysis
- Business Insight Generation

---

## 📁 Repository Structure

```text
mobile-sales-powerbi-dashboard/
│
├── README.md
│
├── PowerBI/
│   ├── Mobile_Sales_Dashboard.pbix
│   └── README.md
│
├── Screenshots/
│   └── Dashboard screenshots
│
└── Documentation/
    └── Business_Insights.md
```

---

## 🚀 How to Explore

1. Open the `.pbix` file from the **PowerBI** folder.
2. Open it using **Microsoft Power BI Desktop**.
3. Interact with the slicers and filters.
4. Explore sales, product, payment, rating, geographic and time-based analysis.
5. Compare current performance with the same period last year.

---

## 👨‍💻 Project Ownership

This dashboard was **independently developed as a portfolio project** to demonstrate practical Power BI, DAX, data transformation, visualization, and business-analysis skills.

The focus was not only on creating visuals, but on designing a reporting interface that can help a stakeholder move from **"What happened?" to "Where did it happen?" and "How is performance changing?"**.

---

## ⭐ Why This Project Matters

This project demonstrates the ability to turn transaction-level data into an **interactive business reporting solution** — a core skill for entry-level **Data Analyst, MIS Executive, and Business Intelligence** roles.

**Key takeaway:** The dashboard is designed for exploration and decision support, not just visual presentation.
