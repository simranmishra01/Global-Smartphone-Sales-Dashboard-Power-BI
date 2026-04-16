# 📱 Global Smartphone Sales Analysis Dashboard — Power BI 

> Interactive sales intelligence across brands, cities, models, and customer segments.

## 📌 Overview

This Power BI dashboard delivers end-to-end visibility into global smartphone sales — covering brand performance, model-level revenue, city-wise demand, customer demographics, and payment trends. Designed for retail analysts, category managers, and business strategists who need fast, filterable insight without digging through raw data.

**Key focus areas:** Brand analysis · Model-level revenue · City ranking · Age segmentation · Payment method · Monthly trends · Customer ratings

---

## 📊 Dashboard Preview

[Global Smartphone Sales Dashboard]((https://github.com/simranmishra01/Global-Smartphone-Sales-Dashboard-Power-BI/blob/main/snapshot%20of%20the%20smartphone%20sales%20dashboard.png) )

---

## 🔢 Top-Line Metrics

| Metric | Value | Note |
|---|---|---|
| Total Sales | **3M** | All brands combined |
| Top Brand | **Vivo** | 41.67% market share |
| Top City | **Delhi** | 2.5M in sales |
| Average Sale | **210K** | Per transaction |

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| **Power BI Desktop** | Main visualization and report authoring platform |
| **Power Query** | Data cleaning, reshaping, and transformation |
| **DAX (Data Analysis Expressions)** | Calculated measures, KPIs, and conditional logic |
| **Data Modeling** | Cross-table relationships for filtering and aggregation |
| **File Format** | `.pbix` for development, `.png` for dashboard previews |

---

## 🚀 Features & Highlights

### Business Problem

The global smartphone retail industry lacks centralized visibility into cross-brand sales performance, customer demographics, and regional demand patterns. Analysts and decision-makers struggle to identify which brands dominate specific cities, which models drive the most revenue, or how payment preferences vary across customer segments.

## 📂 Dataset Source

Dataset used for this project is a sample smartphone sales dataset containing transactional sales records across brands, models, cities, customer ratings, and payment methods.

Key fields include:

- Brand and Model
- City
- Sales Amount
- Quantity Sold
- Customer Age Group
- Payment Method
- Monthly Sales Data
- Customer Ratings

### Goal of the Dashboard

To provide an interactive, filterable Power BI dashboard that surfaces key sales insights across brands, cities, time periods, and customer profiles — enabling faster, evidence-based business decisions.

### Key Visuals

| Visual | Type | Insight |
|---|---|
| Top-line metrics | KPI Cards | Total sales, transactions, quantity sold, avg. sale value |
| Sales by smartphone model | Bar Chart | Vivo S1 leads at 0.60M; OnePlus 8T lowest at 0.10M |
| Sales by month | Line Chart | Seasonal peaks in May (0.46M) and October (0.47M) |
| Sales by brand | Donut Chart | apple 41.67% · Samsung 25% · OnePlus 16.67% · vivo 8.33% · Xiaomi 8.33% |
| Sales by age group | Bar Chart | Adults dominate at 2.5M; Senior segment near zero |
| Top selling city | Bar Chart | Delhi at 2.5M — strong regional concentration |
| Payment method | Donut Chart | UPI 41.67% · Debit Card 33.33% · Cash 25% |
| Dynamic filters | Slicers | Year, month, brand, model, city, and customer rating |

### Filters / Slicers Available

- Year selector (2021, 2022, 2023, 2024)
- Month selector (January–December)
- Brand dropdown
- Customer Rating dropdown
- Mobile Model dropdown
- City dropdown

---

## 📈 Brand Breakdown

```
Apple     ████████████████████░░░░░░░░░░░░░░░░░░░  41.67%
Samsung   █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░  25.00%
OnePlus   ████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  16.67%
vivo      ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   8.33%
xiaomi    ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   8.33%
```

---

## 💡 Key Business Insights

1. **Vivo dominates at 41.67%** — Strong model-level and brand-level penetration across the market. Vivo S1 alone generates 0.60M, nearly 2x the next best model (Galaxy S21 at 0.47M).

2. **Delhi drives regional demand** — At 2.5M in sales, Delhi is the clear top-performing city. This geographic concentration signals an opportunity to expand demand in other cities.

3. **Senior segment is near zero** — Adult customers account for virtually all sales (2.5M). The Senior demographic represents a significant untapped growth opportunity with targeted product and pricing strategies.

4. **UPI leads payment adoption** — With 41.67% share, UPI is the most popular payment method, reflecting strong digital payment adoption. Cash accounts for only 25%.

5. **Seasonal peaks in May & October** — Sales spike sharply at 0.46M (May) and 0.47M (October). Inventory stocking and promotional campaigns should be timed to these windows.

6. **Mid-range models drive volume** — The top 3 models (Vivo S1, Galaxy S21, Vivo V20) collectively account for the majority of units sold, suggesting customers favor value-tier devices.

---

## 🗂️ Project Structure

```
Global-Smartphone-Sales-Analysis-Dashboard-PowerBI/
│
├── SmartphoneSalesDashboard.pbix   # Power BI project file
├── dashboard-preview.png           # Dashboard screenshot
├── data/
│   └── smartphone_sales.csv        # Raw dataset
└── README.md
```

---

## 🙋‍♀️ Author

**Simran Mishra**  
Built using Power BI  
Connect on [LinkedIn](www.linkedin.com/in/simran-mishra-a21368276)
⭐ Star this repository if you found it useful!
