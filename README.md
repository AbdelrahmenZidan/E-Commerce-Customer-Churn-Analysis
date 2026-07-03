# E-Commerce Customer Churn Analysis

<p align="center">
  <img src="Images/Hero_Banner.png" alt="Hero Banner">
</p>

End-to-end Excel project analyzing customer churn using data cleaning, pivot tables, dashboards, and business insights.

---

## 📑 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Business Problem](#-business-problem)
- [📂 Dataset Overview](#-dataset-overview)
- [🧹 Data Cleaning](#-data-cleaning)
- [📋 Data Audit](#-data-audit)
- [❓ Business Questions](#-business-questions)
- [📊 Pivot Analysis](#-pivot-analysis)
- [📈 Dashboard](#-dashboard)
- [💡 Key Insights](#-key-insights)
- [🚀 Business Recommendations](#-business-recommendations)
- [🛠️ Tools Used](#-tools-used)
- [👨‍💻 Author](#-author)

---

## 📌 Project Overview

This project presents an end-to-end Excel-based data analytics case study focused on **customer churn in an e-commerce platform**.

The goal is to understand customer behavior, identify key drivers of churn, and generate actionable insights to improve customer retention.

The project covers:
- Data cleaning and preprocessing
- Data quality assessment (Data Audit)
- Pivot table analysis
- Interactive dashboard creation
- Business insights and recommendations

---

## 🎯 Business Problem

Customer churn is one of the most critical challenges in e-commerce businesses as it directly impacts revenue and long-term growth.

In this analysis, we aim to answer:

- Why are customers leaving the platform?
- What behaviors indicate a high risk of churn?
- Which factors improve customer retention?
- How can the business reduce churn effectively?

---

## 📂 Dataset Overview

- Total Customers: **5,630**
- Churned Customers: **948**
- Retained Customers: **4,682**
- Overall Churn Rate: **16.84%**

The dataset includes customer behavioral and transactional data such as:
- Tenure
- Order count
- Cashback amount
- App usage
- Complaints
- Device usage

---

## 🧹 Data Cleaning

The dataset was cleaned using business-driven logic:

- Standardized categorical values (e.g., device and category naming)
- Handled missing values using median imputation:
  - Tenure → Median (9)
  - WarehouseToHome → Median (14)
  - HourSpendOnApp → Median
  - OrderAmountHikeFromlastYear → Median (15)
  - CouponUsed → Median (1)
- Verified data consistency and formatting

---

## 📋 Data Audit

A full data quality check was performed:

- Missing Values Analysis
- Duplicate Check → No duplicates found
- Outlier Detection (Cashback Amount) → No significant outliers detected

Result: Dataset is clean and analysis-ready.

---

## ❓ Business Questions

This analysis was structured around key business questions:

- How do customer complaints affect churn?
- Does satisfaction influence retention?
- Which tenure group has the highest churn?
- Does order frequency affect churn?
- Does cashback reduce churn?
- How does app usage affect churn?
- Does number of registered devices impact churn?

---

## 📊 Pivot Analysis

Key insights derived from pivot tables:

- Customers with complaints show significantly higher churn (~31%)
- Low tenure (0–6 months) customers churn the most
- Customers with 1–4 orders are most likely to churn
- Cashback has a positive impact on retention
- App usage hours show weak correlation with churn
- More registered devices may indicate higher churn risk

---

## 📈 Dashboard

An interactive Excel dashboard was created including:

- Complaint vs Churn
- Tenure vs Churn
- Order Count vs Churn
- Cashback vs Churn
- App Usage vs Churn
- Device Usage vs Churn
- Days Since Last Order vs Churn

The dashboard provides a clear visual representation of churn drivers.

---

## 💡 Key Insights

- Customers in the first **6 months** are the most vulnerable to churn
- Complaints significantly increase churn probability
- Low engagement users are more likely to leave
- Cashback incentives help improve retention
- Device overuse may indicate suspicious or multi-account behavior

---

## 🚀 Business Recommendations

- Improve onboarding experience for new customers (first 6 months)
- Actively resolve customer complaints to reduce churn risk
- Introduce loyalty programs for low-order customers
- Optimize cashback strategies to increase retention
- Monitor multi-device usage patterns for potential abuse

---

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Data Cleaning Techniques
- Business Analysis Framework
- Dashboard Visualization

---

## 👨‍💻 Author

**Abdelrahmen Zidan**

- Aspiring Data Analyst
- Skilled in Excel, SQL, and Data Visualization
- Passionate about turning data into business insights

---

⭐ If you found this project useful, feel free to star the repository!
