# Fraud Analysis Project — PBL MSIB Batch 7  
### Bitlabs Academy x Paper.id  
**By: Achmad Ikhsan Alghifari, Jauzay Audy S, Ni Made Ochiana S P**

## Project Overview  
This repository contains the final project for **PBL (Project-Based Learning) MSIB Batch 7** at **Bitlabs Academy**, focusing on **fraud analysis in digital payments** using datasets inspired by **Paper.id**.

The goal of this project is to identify fraudulent transaction patterns, detect suspicious buyer–seller relationships, and analyze potential promotion exploitation using **advanced SQL**, **data cleaning**, **feature engineering**, and **exploratory data analysis (EDA)**.

---

## Case Study Background  
A fintech company processes millions of digital transactions between buyers and sellers. Recently, the company observed an **increase in fraudulent activities** impacting revenue and customer trust.

### Objectives:
- Detect suspicious transaction patterns  
- Identify unusual buyer–seller relationships  
- Uncover promotion exploitation  
- Provide actionable insights to reduce fraud risk  

---

## Dataset Description  
The analysis uses four key datasets:

### **1. Digital Payment Transaction Data**
Contains transaction-level information such as buyer ID, seller ID, amount, timestamps, payment methods, and associated promotion IDs.

### **2. Digital Payment Request Data**
Includes fee details and document type for each transaction.

### **3. Promotion Data**
Lists promotion codes, names, and cashback amounts used in transactions.

### **4. Company Data**
Provides metadata for each company (buyer/seller), including KYC/KYB status, verification flags, fraud flags, blacklist status, and registration time.

---

## Task 2 — Data Cleaning & Feature Engineering  

### **Data Cleaning**
- Handled missing values, outliers, and duplicates  
- Standardized timestamp formats  
- Identified suspicious missing fields in `user_fraud_flag` and `blacklist_account_flag`  
- Ensured consistent data types across datasets  

### **Feature Engineering**
- **Buyer–Seller Relationship Score**  
  Measures interaction frequency between buyers and sellers to identify unusual patterns  
- **Transaction Frequency Metrics**  
  Detects irregular transaction timing (spikes, bursts, unusual gaps)  
- **Promotion Exploitation Indicator**  
  Flags repeated or abnormal use of specific promo codes  
- **Scaling & Normalization**  
  Applied normalization on transaction amounts and time intervals for improved analysis  

---

## Task 3 — Exploratory Data Analysis (EDA)  

### **Fraud Pattern Exploration**
- Analyzed transaction amount distribution  
- Identified repeated transactions and high-value anomalies  
- Observed frequent buyer–seller interactions  
- Investigated promotion usage patterns and potential misuse  

### **Visualizations (Matplotlib & Seaborn)**
- Time-series trends to identify suspicious spikes  
- Buyer–seller network graph to spot suspicious relationships  
- Promo usage visualizations (heatmaps & bar charts)  
- Histograms, boxplots, and distribution plots for anomaly detection
