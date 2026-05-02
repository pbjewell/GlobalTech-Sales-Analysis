# 📊 GlobalTech Sales Analysis (Module 9)

## 📌 Overview

This project is part of **Module 9: Introduction to Data Analysis with Pandas**.
It analyzes quarterly sales data for a fictional company, **GlobalTech**, using **Python**, **Pandas**, and **NumPy**.

The script performs data exploration, filtering, aggregation, and business analysis to generate insights and a formatted sales report.

---

## 🗂️ Dataset Description

The dataset simulates sales records with the following columns:

* **Date** – Sale date (YYYY-MM-DD)
* **Region** – Sales region (North America, Europe, Asia, Latin America)
* **Store** – Store ID
* **Category** – Product category
* **Product** – Product name
* **Units** – Number of units sold
* **Unit_Price** – Price per unit (USD)
* **Total_Sales** – Total revenue (USD)
* **Promotion** – Whether item was on promotion (Yes/No)

⚠️ Note: The dataset is **simulated in-code** using `StringIO` and includes **missing values (NaN)** for analysis practice.

---

## ⚙️ Features & Analysis

### 🔹 1. Data Exploration

* Load dataset into a Pandas DataFrame (`sales_df`)
* View:

  * First 5 rows
  * Data types and structure
  * Dataset dimensions
  * Summary statistics

---

### 🔹 2. Basic Metrics

* **Total Units Sold**
* **Total Revenue**
* **Average Unit Price**

---

### 🔹 3. Data Filtering

Created filtered datasets:

* `na_sales` → North America sales
* `high_volume_sales` → Units > 20
* `phonex_promo` → PhoneX on promotion
* `feb_sales` → February 2024 sales

---

### 🔹 4. Aggregations & Insights

* Best-selling product (`best_product`)
* Revenue by region (`sales_by_region`)
* Average units per category (`avg_units_by_category`)

---

### 🔹 5. Promotion Analysis

Compares:

* Average sales (promo vs non-promo)
* Total revenue from promotions

Stored in:

```python
promo_comparison
```

---

### 🔹 6. Missing Data Analysis

* Count of missing values per column (`missing_counts`)
* Percentage of missing data (`missing_percentages`)

---

### 🔹 7. Advanced Insights

* Top-performing category by region
* Average price per category
* Product revenue contribution (% of total sales)

---

### 🔹 8. Final Report Output

The script prints a formatted **GlobalTech Q1 2024 Sales Report**, including:

* Overall performance
* Regional revenue breakdown
* Category performance
* Promotion effectiveness
* Data quality report
* Business recommendations

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**

---

## ▶️ How to Run

1. Install dependencies:

```bash
pip install pandas numpy
```

2. Run the script:

```bash
python your_script_name.py
```

---

## 📊 Example Output

The program generates a report like:

```
GLOBALTECH Q1 2024 SALES ANALYSIS REPORT

Overall Performance:
- Total Revenue: $XXX,XXX.XX
- Total Units Sold: XXX
- Average Sale Value: $XXX.XX
```

---

## 💡 Key Insights

* North America and Europe generate the highest revenue
* Promotions impact total revenue but not always average sale value
* Some categories outperform others in both volume and pricing
* Missing data exists and should be addressed for better accuracy

---

## 📈 Business Recommendations

1. Strengthen marketing campaigns to improve sales performance
2. Focus on high-performing regions for maximum ROI
3. Improve data quality by addressing missing values

---

## 🎯 Learning Objectives

This project demonstrates:

* Data loading and exploration with Pandas
* Filtering and conditional selection
* Grouping and aggregation
* Handling missing data
* Generating business insights from raw data

---

## ⚠️ Notes

* Dataset is **synthetic and for educational purposes only**
* Some values are intentionally missing to simulate real-world scenarios

---

## 👤 Author

Student Project – Data Analytics Coursework
