# EV-DATABASE---EXPLORATORY-DATA-ANALYSIS
# 🚗 EV Market Data Analysis

## 📌 Project Overview
This project focuses on analyzing an Electric Vehicle (EV) dataset to uncover meaningful insights about pricing, performance, and value-for-money across different EV models available in the European market.

The project demonstrates **end-to-end data analytics skills**, including data cleaning, preprocessing, exploratory data analysis (EDA), and insight generation using Python.

---

## 🎯 Objectives
- Clean and preprocess raw EV market data
- Handle missing, inconsistent, and unstructured values
- Analyze EV pricing trends across countries
- Compare vehicle specifications such as acceleration, weight, cargo volume, and towing capacity
- Identify top-performing EV models based on value-for-money metrics

---

## 📂 Dataset Description
The dataset includes the following key attributes:
- Car name & brand
- Prices across multiple countries (Germany, UK, Netherlands)
- Acceleration (0–100 km/h)
- Weight (kg)
- Cargo volume (liters)
- Towing capacity
- Performance and efficiency metrics

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas** – data manipulation & cleaning  
- **NumPy** – numerical computations  
- **Regex (re)** – text and unit cleaning  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook** – analysis environment  

---

## 🧹 Data Cleaning & Preprocessing
Key preprocessing steps performed:
- Removed units such as `kg`, `sec`, `L` using regular expressions
- Converted textual numeric fields into proper numeric data types
- Replaced missing price values with **median** values to avoid skewness
- Standardized decimal formats (`,` → `.`)
- Handled missing and inconsistent records efficiently

### Why Median Imputation?
Median was chosen over mean because:
- It is robust to outliers
- EV prices vary significantly across brands
- Prevents distortion caused by extremely high-priced luxury EVs

---

## 📊 Exploratory Data Analysis (EDA)
The analysis includes:
- Country-wise EV price comparison
- Acceleration vs price analysis
- Value-for-money ranking by car model
- Distribution analysis of EV specifications
- Brand-level performance comparison

---

## 🔍 Key Insights
- Certain mid-range EVs offer significantly better value-for-money than premium models
- EV prices vary notably across European countries
- Performance metrics such as acceleration are not always directly proportional to price
- Median-based imputation improved overall dataset reliability

---

## 🚀 Project Outcomes
- Built a clean, structured EV database ready for analysis
- Generated actionable insights for EV market comparison
- Demonstrated strong data cleaning, EDA, and analytical reasoning skills
- Suitable for real-world business and market analysis use cases

---

## 📁 Repository Structure
