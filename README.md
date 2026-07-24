# 📊 SaaS/E-Commerce Cohort Retention & Customer Lifetime Value (CLTV) Analysis

## 🚀 Project Overview

Customer retention is one of the most important growth metrics for SaaS and e-commerce businesses. Acquiring new customers is significantly more expensive than retaining existing ones. This project uses Cohort Analysis to measure customer retention over time and Customer Lifetime Value (CLTV) analysis to estimate long-term customer profitability.

Using the **Online Retail II** dataset, this project identifies customer churn patterns, measures retention rates across acquisition cohorts, and provides actionable business insights to improve customer loyalty and revenue.

---

## 🎯 Project Objectives

- Clean and preprocess transactional retail data
- Perform customer cohort analysis
- Measure monthly customer retention
- Calculate Customer Lifetime Value (CLTV)
- Visualize customer retention trends
- Generate business recommendations based on data
- Build an interactive Power BI dashboard (Final Phase)

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SQL**
- **Power BI**
- **Google Colab / Jupyter Notebook**
- **Git & GitHub**

---

## 📂 Repository Structure

```text
saas-cohort-retention-cltv-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_cohort_retention_analysis.ipynb
│
├── images/
│   ├── retention_heatmap.png
│   └── retention_curve.png
│
├── dashboard/
├── reports/
├── sql/
│
├── README.md
└── requirements.txt
```

---

# 📅 Project Progress

## ✅ Week 1 – Data Cleaning & Feature Engineering

### Completed Tasks

- Loaded and explored the Online Retail II dataset
- Removed missing Customer IDs
- Removed cancelled/refunded transactions
- Removed invalid quantities and prices
- Removed duplicate records
- Converted InvoiceDate to datetime format
- Created Revenue column
- Generated Invoice Month
- Generated Cohort Month
- Calculated Cohort Index

### Deliverable

- Cleaned and analysis-ready transactional dataset

---

## ✅ Week 2 – Cohort Retention Analysis

### Completed Tasks

- Built Customer Cohort Matrix
- Calculated Monthly Customer Retention
- Generated Retention Percentage Matrix
- Created Customer Retention Heatmap
- Created Average Retention Decay Curve
- Performed Customer Churn Analysis
- Documented Business Insights

### Key Insights

- Customer retention drops significantly after the first month.
- A small percentage of customers continue purchasing over many months, indicating a loyal customer segment.
- Early customer engagement is critical to improving long-term retention.

---

## 📈 Visualizations

### Customer Cohort Retention Heatmap

![Customer Cohort Retention Heatmap](images/retention_heatmap.png)

### Average Retention Decay Curve

![Average Retention Curve](images/retention_curve.png)

---

## 📌 Dataset

**Online Retail II Dataset**

The dataset contains transactional data from a UK-based online retailer between 2009 and 2011.

**Source:**

https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

> **Note:** The raw dataset is not included in this repository due to its size and Kaggle's distribution policy.

---

## 🚧 Upcoming Work

### Week 3 – Customer Lifetime Value (CLTV)

- Average Order Value (AOV)
- Purchase Frequency
- Customer Value
- Historical CLTV Calculation
- Customer Segmentation

### Week 4 – Business Intelligence & Reporting

- Power BI Dashboard
- Executive Summary
- Strategic Business Recommendations
- GitHub Project Documentation

---

## 📄 License

This project was developed as part of a **Data Analytics Internship** and is intended for educational and portfolio purposes.
