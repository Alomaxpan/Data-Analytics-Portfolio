# 🛒 Customer Segmentation using RFM Analysis

## 📌 Project Overview

This project performs **Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis** on an e-commerce dataset.

The goal is to identify high-value customers, understand purchasing behavior, and generate actionable insights to improve business decisions such as marketing, retention, and revenue optimization.

---

## 🎯 Business Problem

E-commerce companies generate large volumes of transactional data but often lack clear customer insights.

This project answers key business questions:

* Who are the most valuable customers?
* Which customers are likely to churn?
* How can customers be segmented for targeted marketing?

---

## 📊 Dataset

* **Source:** UCI Machine Learning Repository
* **File Used:** Online Retail Dataset
* **Description:** Transactional data of an online retail store

### Key Features:

* CustomerID
* InvoiceDate
* Quantity
* UnitPrice
* Country

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Removed missing Customer IDs
* Removed negative quantities (returns)
* Removed invalid price values

### 2. Feature Engineering

* Created **Revenue = Quantity × UnitPrice**
* Converted date columns to datetime format

### 3. RFM Calculation

* **Recency:** Days since last purchase
* **Frequency:** Number of transactions
* **Monetary:** Total spending

### 4. Customer Segmentation

Customers were segmented into:

* 🟢 Best Customers
* 🔵 Loyal Customers
* 🟡 Regular Customers
* 🔴 At Risk Customers

---

## 📈 Key Insights

* Best customers contribute the highest revenue and should be prioritized for retention.
* Loyal customers show consistent purchasing behavior and are ideal for upselling.
* At-risk customers have not purchased recently and need re-engagement strategies.
* Regular customers can be converted into loyal customers through targeted campaigns.

---

## 📊 Visualizations

The project includes:

* RFM distribution plots
* Customer segment distribution
* Revenue contribution by segment
* Scatter plots for behavioral analysis

---

## 🚀 Business Impact

This analysis can help businesses:

* Improve customer retention
* Increase revenue through targeted marketing
* Identify high-value customer segments
* Reduce churn

---

## 📁 Project Structure

Customer-Segmentation-RFM
│
├── data/
│   └── Online Retail.xlsx
│
├── notebook/
│   └── rfm_customer_segmentation.ipynb
│
└── README.md

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Upload the dataset (`Online Retail.xlsx`)
3. Run all cells

---

## 💡 Future Improvements

* Apply Machine Learning clustering (K-Means)
* Build an interactive dashboard (Power BI / Tableau)
* Automate customer segmentation pipeline

---

## 👨‍💻 Author

**Gaurav**
Aspiring Data Analyst / Data Scientist
