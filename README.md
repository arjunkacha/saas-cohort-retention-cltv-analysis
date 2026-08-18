# 📊 SaaS/E-Commerce Cohort Retention & Customer Lifetime Value (CLTV) Analysis

## 🚀 Project Overview

Customer retention is one of the most important growth metrics for SaaS and e-commerce businesses. Acquiring new customers is significantly more expensive than retaining existing ones. This project applies **Cohort Analysis** to measure customer retention over time and **Customer Lifetime Value (CLTV)** analysis to estimate long-term customer profitability.

Using the **Online Retail II** dataset, this project identifies customer churn patterns, evaluates retention across acquisition cohorts, segments customers based on lifetime value, and provides actionable business insights to improve customer loyalty and maximize revenue.

---

# 🎯 Project Objectives

- Clean and preprocess transactional retail data
- Perform Exploratory Data Analysis (EDA)
- Build customer cohort retention matrix
- Measure monthly customer retention
- Calculate Customer Lifetime Value (CLTV)
- Segment customers based on CLTV
- Visualize customer retention and customer value
- Build an interactive Power BI dashboard
- Generate business recommendations

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Power BI
- Google Colab / Jupyter Notebook
- Git & GitHub

---

# 📂 Repository Structure

```text
saas-cohort-retention-cltv-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── project_2_cohort_retention_cltv_analysis.ipynb
│
├── images/
│   ├── retention_heatmap.png
│   ├── retention_curve.png
│   ├── average_cltv_by_segment.png
│   ├── cltv_distribution.png
│   ├── customer_segment_distribution.png
│   └── top_10_customers_cltv.png
│
├── dashboard/
│   ├── executive_overview.png
│   ├── customer_analysis.png
│   └── saas-cohort-retention-cltv-analysis.pbix
│
├── reports/
├── sql/
│
├── README.md
├── requirements.txt
└── .gitignore
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
- Created Revenue feature
- Generated Invoice Month
- Generated Cohort Month
- Calculated Cohort Index
- Prepared analysis-ready dataset

### Deliverable

- Cleaned and feature-engineered transactional dataset ready for customer analytics

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
- A small percentage of customers continue purchasing over many months.
- Early customer engagement plays a critical role in long-term retention.

---

## ✅ Week 3 – Customer Lifetime Value (CLTV) Analysis

### Completed Tasks

- Calculated Average Order Value (AOV)
- Calculated Purchase Frequency
- Estimated Customer Lifespan
- Calculated Historical Customer Lifetime Value (CLTV)
- Segmented customers into value-based categories
- Visualized CLTV distribution
- Identified top high-value customers
- Generated business insights and recommendations

### Key Insights

- Premium customers contribute a significant share of overall revenue.
- Customers with higher purchase frequency generate substantially greater lifetime value.
- Extending customer lifespan has a direct positive impact on CLTV.
- Customer segmentation enables targeted marketing and personalized retention strategies.

---

# 📈 Data Visualizations

### Customer Cohort Retention Heatmap

![Customer Cohort Retention Heatmap](images/retention_heatmap.png)

### Average Retention Curve

![Average Retention Curve](images/retention_curve.png)

### Customer Lifetime Value Distribution

![Customer Lifetime Value Distribution](images/cltv_distribution.png)

### Average CLTV by Customer Segment

![Average CLTV by Customer Segment](images/average_cltv_by_segment.png)

### Customer Segment Distribution

![Customer Segment Distribution](images/customer_segment_distribution.png)

### Top 10 Customers by CLTV

![Top 10 Customers by CLTV](images/top_10_customers_cltv.png)

---

# 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to transform the cohort retention and CLTV analysis into an executive-friendly business intelligence report.

The dashboard contains two analytical pages:

## 1. Executive Overview

The Executive Overview provides a high-level summary of customer and revenue performance.

### Key Components

- Total Customers
- Total Revenue
- Total Orders
- Average Order Value
- Customer Retention Analysis
- Monthly Revenue Trends
- Customer Segment Analysis
- Cohort Retention Analysis
- Key Business Insights

### Dashboard Preview

![Power BI Executive Overview](dashboard/executive_overview.png)

---

## 2. Customer Analysis

The Customer Analysis page provides a deeper view of customer behavior, segmentation, and lifetime value.

### Key Components

- Customer Lifetime Value Analysis
- CLTV Distribution
- Customer Segment Distribution
- Revenue by Customer Segment
- Customer Lifespan Analysis
- Customer-level Analysis
- Key Business Insights

### Dashboard Preview

![Power BI Customer Analysis](dashboard/customer_analysis.png)

---

# 💡 Business Insights & Recommendations

The combined cohort retention and CLTV analysis provides several actionable business insights.

## Customer Retention

- Customer retention declines significantly after the initial purchase period.
- Improving early customer engagement can help increase long-term retention.
- Cohort analysis can be used to identify customer groups with stronger or weaker retention behavior.

## Customer Lifetime Value

- Higher purchase frequency contributes significantly to customer lifetime value.
- Customers with longer lifespans have greater potential lifetime value.
- Value-based segmentation enables businesses to prioritize high-value customers.

## Strategic Recommendations

- Develop targeted retention campaigns for customers showing early signs of churn.
- Increase repeat purchase frequency through personalized offers and engagement campaigns.
- Prioritize high-value customer segments with loyalty and retention programs.
- Use customer segmentation to allocate marketing resources more effectively.
- Monitor cohort retention and CLTV together to evaluate long-term customer profitability.

---

# 📌 Dataset

**Dataset:** Online Retail II

The dataset contains transactional records of a UK-based online retailer between **December 2009 and December 2011**.

**Source:**

[Online Retail II – Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

> **Note:** The raw dataset is not included in this repository because of its size and Kaggle's distribution policy.

---

# 🎯 Project Outcome

This project combines **customer retention analysis, cohort analysis, CLTV modeling, customer segmentation, data visualization, and business intelligence** into a complete end-to-end analytics solution.

The final solution demonstrates how transactional customer data can be transformed into actionable insights for improving:

- Customer Retention
- Customer Lifetime Value
- Customer Segmentation
- Revenue Growth
- Customer Loyalty
- Marketing Strategy

---

# ✅ Project Completion

## Week 4 – Business Intelligence & Reporting

### Completed Tasks

- Interactive Power BI Dashboard
- Executive Overview
- Customer Analysis Dashboard
- KPI Cards
- Customer Retention Analysis
- CLTV Analysis
- Customer Segmentation
- Executive Summary
- Strategic Business Recommendations
- Key Business Insights
- Dashboard Preview Images
- Final Project Documentation

---

# 📄 License

This project was developed as part of a **Data Analytics Internship** and is intended for educational and portfolio purposes.
