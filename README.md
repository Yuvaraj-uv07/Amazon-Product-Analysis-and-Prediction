
# 🛒 Amazon Product Data Extraction and Analysis

An end-to-end Data Science project that demonstrates how to collect, clean, analyze, and model product data from Amazon using web scraping, SQL, and machine learning. The project focuses on fashion accessories and transforms unstructured data into business insights and predictive models.

---

## 📌 Table of Contents

1. [Introduction](#introduction)  
2. [Objectives](#objectives)  
3. [Tools and Technologies](#tools-and-technologies)  
4. [Data Collection Methodology](#data-collection-methodology)  
5. [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)  
6. [Exploratory Data Analysis](#exploratory-data-analysis)  
7. [Key Insights](#key-insights)  
8. [SQL Integration](#sql-integration)  
9. [Dashboard in Power BI](#dashboard-in-power-bi)  
10. [Machine Learning](#machine-learning)  
11. [Conclusion](#conclusion)

---

## 1️⃣ Introduction

In today’s digital world, data is the new oil — especially in the e-commerce space. Platforms like **Amazon** generate vast amounts of product and customer data that can offer critical insights into **market behavior**, **pricing strategies**, and **consumer preferences**.

This project demonstrates how to extract and analyze Amazon product data using tools like **Selenium**, **BeautifulSoup**, **Pandas**, and **Power BI**, and further applies **machine learning** models for **price prediction** and **Prime product classification**.

---

## 2️⃣ Objectives

- Scrape product data from Amazon search pages  
- Collect key attributes: title, price, rating, review count, etc.  
- Clean and preprocess data  
- Perform exploratory data analysis (EDA)  
- Extract actionable business insights  
- Apply regression models to predict product price  
- Apply classification models to predict Prime eligibility  

---

## 3️⃣ Tools and Technologies

- **Python** – Core language for scraping, analysis, and modeling  
- **Selenium** – Browser automation for dynamic content  
- **BeautifulSoup** – HTML parsing and data extraction  
- **Pandas & NumPy** – Data manipulation and wrangling  
- **MySQL/SSMS** – Database storage and connectivity  
- **Scikit-learn** – Machine learning models  
- **Matplotlib & Seaborn** – Visualizations during EDA  
- **Power BI** – Interactive dashboards  
- **Jupyter Notebook** – Development and analysis environment  

---

## 4️⃣ Data Collection Methodology

- Launch headless Chrome browser using Selenium  
- Navigate Amazon search result pages with specific keywords  
- Extract product titles, prices, ratings, and review counts  
- Handle pagination to scrape multiple pages  
- Store the scraped data into a structured DataFrame  

---

## 5️⃣ Data Cleaning & Preprocessing

- Handle missing or null values  
- Convert strings to numeric data types (price, rating, reviews)  
- Remove duplicates and outliers  
- Normalize column formats  
- Prepare clean dataset for analysis and modeling  

---

## 6️⃣ Exploratory Data Analysis

Visual insights include:

- **Price Distribution**: Most products fall into mid-range prices  
- **Rating Distribution**: Majority of products have ratings between 3.5 to 4.5  
- **Popularity Analysis**: High review counts usually signal top products  
- **Category Breakdown**: Fashion accessories dominate (Men, Women, Kids)

---

## 7️⃣ Key Insights

- Moderately priced products often have better ratings  
- High review counts are typically associated with well-known brands  
- No strong correlation between price and rating — buyers prioritize quality and usability  
- Women’s accessories are the most diverse and popular segment  

---

## 8️⃣ SQL Integration

- Cleaned data is stored in **MySQL** using `mysql-connector`  
- Table schema includes: Category, Brand, Product Name, Price, Rating, Discount, Availability, Product URL, Date  
- Supports seamless integration with Power BI and SQL-based analytics  

---

## 9️⃣ Dashboard in Power BI

An interactive Power BI dashboard was created to visualize and explore:

- Average prices and rating distribution  
- Discount percentages  
- Availability and product segments  
- Drilldown filters: Category, Brand, Price Range  

> 💡 Connects directly to MySQL for real-time data refresh.

---

## 🔟 Machine Learning

### 📈 Price Prediction  
- **Multiple Linear Regression** as baseline  
- Enhanced using:
  - **Ridge Regression (L2)**  
  - **Lasso Regression (L1)**  
  - **ElasticNet (L1 + L2)**  

### ✅ Prime Classification  
- Models Used:
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
  - **Decision Tree**
  - **Random Forest**
  - **XGBoost**

> Ensemble models provided the best classification results for Prime eligibility.

---

## 1️⃣1️⃣ Conclusion

This project successfully showcases how to:
- Scrape real-world product data from Amazon  
- Clean and preprocess unstructured web data  
- Perform data analysis and build visual dashboards  
- Apply machine learning to derive meaningful predictions  



