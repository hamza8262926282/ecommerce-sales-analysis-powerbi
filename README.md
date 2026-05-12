```md
## 📊 Power BI Dashboard

<p align="center">
  <img src="dashboard/dashboard_preview.png" width="100%">
</p>
```

```md
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/doc/)

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)](https://learn.microsoft.com/en-us/power-bi/)

[![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange)](https://scikit-learn.org/stable/documentation.html)

[![Prophet](https://img.shields.io/badge/Forecast-Prophet-green)](https://facebook.github.io/prophet/docs/quick_start.html)

[![Status](https://img.shields.io/badge/Status-Complete-brightgreen)](https://github.com/hamza8262926282)
```



> End-to-end data analytics project on the Olist Brazilian E-Commerce dataset.
> Python handles data cleaning, RFM segmentation, KMeans clustering, and 90-day
> revenue forecasting. Power BI delivers 4-page executive dashboard.

---

## 📊 Power BI Dashboard



| Page | Description |
|------|-------------|
| 🏠 Executive Overview | Total Revenue, Orders, Customers, AOV · Revenue by Category · Delivery Status |
| 👥 Customer Intelligence | RFM Cluster Donut · Cluster Revenue Bar · Segment Profile Table |
| ⚙️ Operational Performance | State Revenue Map · Delivery Scatter · Avg Delivery Time KPI |
| 📈 Forecasting | 90-Day Revenue Forecast · Future Revenue KPI Card |

---

## 🐍 Python Analysis (main_code.ipynb)

### What the notebook covers:

1. **Data Loading & Merging** — 5 Olist datasets merged into one analytical dataset
2. **Data Cleaning** — datetime conversion, delivered orders filter, missing value handling
3. **Feature Engineering** — total price, delivery time, delivery status (On-Time/Delayed)
4. **Outlier Removal** — IQR method on transaction prices
5. **KPI Calculations** — Total Revenue, Total Orders, Customers, AOV, Monthly Growth %
6. **RFM Customer Segmentation** — Recency, Frequency, Monetary scoring
7. **KMeans Clustering** — 4 customer segments with StandardScaler normalization
8. **Sales Forecasting** — Facebook Prophet model · 30-day train-test split · 90-day forecast
9. **Model Evaluation** — MAE & RMSE metrics
10. **Export for Power BI** — 5 clean CSV files generated

---

## 🗂️ Dataset

**Source:** [Olist Brazilian E-Commerce Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

| File | Description |
|------|-------------|
| olist_orders_dataset.csv | Order-level data with timestamps and status |
| olist_order_items_dataset.csv | Product & freight pricing per order |
| olist_order_payments_dataset.csv | Payment values per order |
| olist_customers_dataset.csv | Customer IDs and states |
| olist_products_dataset.csv | Product categories |

---

## ⚙️ Tech Stack
```md
| Category | Technologies |
|----------|--------------|
| Programming | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Power BI |
| Machine Learning | Scikit-learn, KMeans, StandardScaler |
| Forecasting | Facebook Prophet |
| Data Processing | ETL, EDA, Feature Engineering |
```


---

## 📁 Repository Structure

```
ecommerce-sales-analysis-powerbi/
├── main_code.ipynb          # Python analysis notebook
├── README.md
├── data/                    # Raw Olist CSV datasets
├── outputs/                 # Cleaned + processed exports for Power BI
│   ├── cleaned_ecommerce_data.csv
│   ├── monthly_revenue.csv
│   ├── customer_segmentation_corrected.csv
│   ├── cluster_profile.csv
│   └── sales_forecast.csv
└── dashboard/
    └── README.md            # Power BI download link
```

---

## 🔑 Key Results

- 📦 **Processed** multi-table Olist dataset across 5 merged sources
- 👥 **Segmented** customers into 4 RFM clusters using KMeans
- 📈 **Forecasted** 90-day revenue using Facebook Prophet time-series model
- ⚡ **Delivered** 4-page Power BI dashboard with executive-level KPIs
- 🚚 **Classified** orders as On-Time vs Delayed based on 10-day threshold

---

## 👤 Author
**Muhammad Hamza Awan**  
Data Analyst • Data Scientist • Machine Learning Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/muhammad-hamza-b83748241/)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/hamza8262926282)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:hamzaawan98659@gmail.com)

---

## 📜 License

MIT License — free to use with attribution.
