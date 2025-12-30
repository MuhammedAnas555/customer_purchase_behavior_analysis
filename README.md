# 📊 Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using transactional data to uncover insights related to spending patterns, product preferences, discounts, and subscriptions.

It demonstrates a complete **end-to-end data analytics workflow** using **Python, SQL, and Power BI**, from raw data to business-ready insights.

---

## 📁 Dataset
* **Source:** Publicly available customer shopping dataset  
* **Total Records:** ~3,900 transactions  
* **Total Columns:** 18  

### Key Attributes
* **Customer Details:** Age, Gender, Location, Subscription Status  
* **Purchase Details:** Item Purchased, Category, Size, Color, Season, Purchase Amount  
* **Behavioral Metrics:** Discount Applied, Purchase Frequency, Previous Purchases, Review Rating, Shipping Type  

---

## 🛠 Tools & Technologies
* **Python:** Pandas, NumPy (EDA & Data Cleaning)
* **SQL:** PostgreSQL / MySQL / SQL Server
* **Power BI:** Dashboard & Data Visualization
* **Google Colab:** Development Environment
* **Gamma:** Presentation (PPT)
* **GitHub:** Version Control

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Exploration (Python)
* Loaded dataset using Pandas
* Inspected data structure and summary statistics
* Identified missing and inconsistent values

### 2️⃣ Data Cleaning & Preparation
* Imputed missing review ratings using median values
* Converted column names to `snake_case`
* Removed redundant columns
* Created new features:
  * Age groups
  * Purchase frequency in days

### 3️⃣ SQL Business Analysis
The cleaned data was stored in a relational database and analyzed using SQL to answer business questions such as:
* Revenue by gender
* Subscriber vs non-subscriber spending
* High-spending customers using discounts
* Top-rated and most-purchased products
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group

### 4️⃣ Data Visualization (Power BI)
* Built an interactive dashboard including:
  * Revenue trends
  * Customer demographics
  * Product and category performance
  * Subscription and discount impact
* Added slicers for dynamic analysis

### 5️⃣ Reporting & Presentation
* Created a structured analytical report
* Designed a professional presentation using **Gamma**
---
## 📊 Dashboard
The Power BI dashboard provides:
* KPI-based insights
* Interactive filters
* Clear visuals for non-technical stakeholders

---

## 📈 Key Results & Insights
* Subscribers generate higher average revenue
* Repeat buyers show higher subscription adoption
* Some products are highly discount-dependent
* Specific age groups contribute most to revenue
* Express shipping users tend to spend more
---
