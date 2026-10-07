# Samsung Electronics — Descriptive Analytics

## 📊 Project Overview

This project presents a **Descriptive Analytics analysis of Samsung Electronics** using a synthetic 30-day sales dataset. The analysis focuses on understanding historical business performance through sales trends, product performance, category performance, customer ratings, and regional demand.

> **Important:** Samsung's live sales and customer transaction data is not publicly accessible for this project. Therefore, the report uses a synthetic dataset designed to simulate realistic business operations over a 30-day period. The dataset covers **10 products, 9 product categories, and 5 geographical regions**.  
> Source: Descriptive Analytics Report, page 3.

## 🎯 Objectives

The project answers five key business questions:

1. How did Samsung's daily sales performance change over the 30-day period?
2. Which Samsung products contributed the most to overall sales and revenue?
3. Which Samsung product categories performed the best?
4. How satisfied were customers with Samsung products?
5. How did sales vary across different regions?

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — data processing and KPI calculation
- **Google Colab** — analysis and visualization
- **Microsoft Excel** — data storage
- **ChatGPT** — synthetic dataset generation and report preparation
- **Matplotlib / charts** — data visualization

## 📈 Analysis Covered

### 1. Sales Trends
The 30-day analysis recorded:

- **Total Units Sold:** 25,794
- **Total Revenue:** $27.88 million
- **Average Daily Units Sold:** 860
- **Highest Sales Day:** 14 June 2026 — 1,091 units
- **Lowest Sales Day:** 22 June 2026 — 700 units

Daily sales remained relatively stable, with normal day-to-day fluctuations.

### 2. Best-Selling Products

- **Best-Selling Product by Units:** Galaxy Buds3 Pro — 4,929 units
- **Highest Revenue Product:** Galaxy Z Fold7 — $7.85 million
- **Products Analysed:** 10
- **Average Units Sold per Product:** 2,579

A key finding is that the product selling the most units does **not necessarily generate the most revenue**. Premium products such as the Galaxy Z Fold7 have a much larger revenue contribution.

### 3. Category Performance

- **Highest Performing Category:** Smartphone — 8,013 units
- **Highest Revenue Category:** Smartphone — $9.50 million
- **Second Highest Sales Category:** Earbuds — 4,929 units
- **Second Highest Revenue Category:** Foldable Smartphone — $7.85 million
- **Categories Analysed:** 9

Smartphones and foldable smartphones were the major contributors to the simulated portfolio's revenue.

### 4. Customer Ratings

- **Average Customer Rating:** 4.38 / 5.00
- **Highest Rated Product:** Galaxy Book5 Pro — 4.50
- **Lowest Rated Product:** Galaxy S25 — 4.24

All analysed products maintained average ratings above 4.20, indicating consistently positive customer satisfaction within the simulated dataset.

### 5. Regional Demand

The dataset covers five regions:

- **Highest Units Sold:** North — 5,671 units
- **Highest Revenue:** East — $6.01 million
- **Average Units Sold per Region:** 5,159
- **Average Revenue per Region:** $5.58 million

North had the highest sales volume, while East generated the highest revenue. This shows that higher unit sales do not necessarily mean higher revenue because product mix and product prices matter.

## 🔑 Key Findings

| Area | Key Result |
|---|---|
| Total Sales | 25,794 units |
| Total Revenue | $27.88 million |
| Best-Selling Product | Galaxy Buds3 Pro — 4,929 units |
| Highest Revenue Product | Galaxy Z Fold7 — $7.85 million |
| Best Category | Smartphone — 8,013 units |
| Highest Revenue Category | Smartphone — $9.50 million |
| Average Customer Rating | 4.38 / 5.00 |
| Highest Rated Product | Galaxy Book5 Pro — 4.50 |
| Highest Sales Region | North — 5,671 units |
| Highest Revenue Region | East — $6.01 million |

## 💡 Business Insights

- Samsung's simulated daily sales show relatively stable demand over the 30-day period.
- High unit sales and high revenue are different performance measures.
- Smartphones are the strongest sales and revenue category.
- Premium products make a disproportionately large contribution to revenue.
- Customer ratings are consistently high across the simulated portfolio.
- Regional demand is relatively balanced, but differences in product mix lead to different revenue outcomes.

## 🔮 Future Scope

The report identifies several possible extensions from descriptive to predictive analytics:

- **Sales Forecasting** — predict future product demand using historical sales patterns.
- **Regional Demand Prediction** — forecast regional demand for better inventory and distribution planning.
- **Customer Rating Prediction** — analyse rating trends and potential changes in customer satisfaction.
- **Product Recommendation Analysis** — identify product relationships for personalized marketing and cross-selling.
- **Business Intelligence Dashboard** — build an interactive Power BI or Tableau dashboard for KPI monitoring.

## 📁 Project Structure

```text
Samsung-Descriptive-Analytics/
│
├── README.md
├── dataset/
│   └── samsung_sales_dataset.csv
├── notebooks/
│   └── samsung_descriptive_analytics.ipynb
├── report/
│   └── Descriptive_Analytics_Report.pdf
└── visuals/
    └── charts/
```

> File names above represent a recommended GitHub structure. Include only the files that are actually present in your repository.

## ⚠️ Dataset Disclaimer

This is an **academic analytics project based on synthetic data**. The figures and findings should not be interpreted as Samsung Electronics' actual sales, customer, or financial data.

## 👤 Project Information

**Student:** Utkarsh Saxena  
**Course:** BCA (DS & AI)  
**Section:** BCADS 27  
**Semester:** 3rd Semester  
**Session:** 2026–27  
**Project:** Descriptive Analytics Report — Samsung Electronics
