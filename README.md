# 💳 Credit Card Transaction Analysis Dashboard

## 📌 Project Overview
This project focuses on analyzing large-scale credit card transaction data to uncover insights into **transaction performance, merchant activity, and customer financial behavior**.

An end-to-end analytics solution was built using **Python, MySQL, and Power BI** to transform raw banking data into **interactive dashboards for business decision-making**.

---

## 📂 How to Access Data

Download dataset from Kaggle  
Dataset Link: [Kaggle Dataset](https://www.kaggle.com/datasets/computingvictor/transactions-fraud-datasets?select=users_data.csv).

---

## 🎯 Objectives
- Analyze overall **transaction performance and trends**
- Evaluate **merchant category performance and errors**
- Understand **customer spending behavior**
- Identify **potential high-risk customers**
- Enable **data-driven decision making**

---

## ⚙️ Data Preparation & Modeling

- Processed large-scale dataset (**~10M+ records**) and optimized it to **~5.9M rows**
- Converted **MCC JSON data to CSV using Python (Pandas)**
- Loaded and managed data in **MySQL**
- Connected **Power BI to MySQL** for efficient querying
- Built a **data model and relationships** in Power BI

---

## 📊 Dashboard Insights

### 📈 Transaction Trends
- Observed a decline in transaction revenue after 2017  
- Indicates shift towards **alternative payment methods (UPI, wallets, etc.)**

---

### 🏪 Merchant Analysis
- Grocery & supermarkets have **highest transaction volume**
- High error rates suggest **operational inefficiencies**

---

### 👥 Customer Analysis
- Majority customers fall under **low-risk category**
- Customers with:
  - **Low credit score + high spending**
  → potential **credit risk**

---

### ⚠️ Risk Insights
- Identified **high-risk customers** using:
  - Credit score  
  - Debt exposure  

---

### 💳 Card Strategy Insights
- **Amex & Discover** → premium credit-focused  
- **Visa & Mastercard** → mass-market (credit + debit)

---

## 🖼️ Dashboard Preview

### Overview Dashboard
![Overview](images/overview_dashboard.png)

### Merchant Analysis
![Merchant](images/merchant_analysis.png)

### Customer Analysis
![Customer](images/customer_analysis.png)

---

## 🛠️ Tools & Technologies
- **Power BI** (Dashboard & Visualization)  
- **MySQL** (Data storage & querying)  
- **Python (Pandas)** (Data transformation)  

---

## 📊 Business Impact
- Enabled **data-driven decision making**
- Improved visibility into **transaction performance**
- Helped identify **risk-prone customers**
- Provided insights for **merchant optimization**

---

## 📁 Project Structure
```plaintext
credit-card-analysis/
 ├── Credit_Card_Dashboard.pbix
 ├── README.md
 ├── images/
 ├── data/ (optional)
```
