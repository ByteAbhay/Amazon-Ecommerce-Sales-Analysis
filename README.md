
# Amazon E-commerce Sales Analysis

## 📌 Project Overview

This project analyzes an Amazon e-commerce sales dataset to understand sales performance, order trends, product categories, customer order types, fulfilment methods, and promotion-related patterns.

The analysis was performed using Python, Pandas, NumPy, Matplotlib, and Seaborn, with Excel used for initial data understanding and cleaning.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze overall sales and order performance
- Identify major contributors to sales and quantity
- Analyze order and courier status
- Understand monthly sales and order trends
- Analyze product category performance
- Identify top-performing states
- Compare Amazon and Merchant fulfilment
- Analyze B2B and non-B2B transactions
- Compare records with and without recorded Promotion IDs

---

## 📊 Dataset

The dataset contains Amazon e-commerce order information including:

- Order ID
- Order Date
- Order Status
- Fulfilment
- Sales Channel
- Product Category
- Quantity
- Amount
- Shipping Location
- Courier Status
- Promotion ID
- B2B indicator

The dataset contains approximately **129K records** before data cleaning.

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

- Removed unnecessary columns
- Identified and removed duplicate records
- Investigated missing values
- Standardized data types
- Cleaned shipping city and state values
- Standardized inconsistent state names
- Converted date column to datetime format
- Converted postal codes to string format
- Investigated missing values without making unsupported assumptions

Missing values that could not be reliably inferred were retained as `NaN`.

---

## 🔎 Exploratory Data Analysis

The following areas were analyzed:

### 1. Overall Performance
- Total Orders
- Total Sales
- Total Quantity
- Average Order Value

### 2. Order Status Analysis
Analyzed the distribution of different order statuses such as shipped, cancelled, pending, and returned orders.

### 3. Courier Status Analysis
Analyzed courier-level order distribution including shipped, unshipped, and cancelled orders.

### 4. Time Analysis
Analyzed monthly:

- Orders
- Quantity Sold
- Sales

### 5. Category Analysis
Compared product categories based on:

- Orders
- Quantity
- Sales

### 6. State Analysis
Analyzed sales, order volume, and quantity across Indian states.

### 7. Fulfilment Analysis
Compared Amazon and Merchant fulfilment based on:

- Orders
- Quantity
- Sales

### 8. B2B Analysis
Compared B2B and non-B2B transactions based on:

- Orders
- Quantity
- Sales

### 9. Promotion Analysis
Compared records with a recorded Promotion ID and records where the Promotion ID was missing.

---

## 📈 Key Findings

- The dataset contains **120,378 unique orders**.
- Total sales were approximately **₹7.85 crore**.
- Total quantity sold was **116,646 units**.
- Average Order Value was approximately **₹653**.
- April recorded the highest orders, quantity sold, and sales among the analyzed months.
- The **Set** category recorded the highest sales.
- **Maharashtra** recorded the highest sales, order volume, and quantity sold among states.
- Amazon fulfilment contributed more orders, quantity, and sales than Merchant fulfilment.
- Non-B2B transactions contributed considerably more orders, quantity, and sales than B2B transactions.
- Records with a recorded Promotion ID contributed higher orders, quantity, and sales than records where the Promotion ID was missing.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Excel
- Jupyter Notebook

---

## 📁 Project Structure

```text
Amazon-Ecommerce-Sales-Analysis/
│
├── Amazon_Ecommerce_Analysis.ipynb
├── README.md
└── dataset/
    └── Amazon_Sales.xlsx
