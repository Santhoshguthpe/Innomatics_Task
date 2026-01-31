# 🍽 Food Delivery Data Integration & Analysis Project

This project demonstrates how to combine multiple real-world datasets stored in **different file formats** (CSV, JSON, SQL) into a **single unified dataset** for analysis.  
It also focuses on understanding **customer behavior, restaurant performance, and revenue trends**.

---

## 📁 Files Provided

The project uses three different data sources:

### 📂 1. orders.csv (Transactional Data)
Contains order-level information such as:
- Order ID
- User ID
- Restaurant ID
- Order date
- Total order amount

### 📂 2. users.json (User Master Data)
Contains user-related information:
- User ID
- User name
- City
- Membership type (Gold / Regular)

### 📂 3. restaurants.sql (Restaurant Master Data)
Contains restaurant details:
- Restaurant ID
- Restaurant name
- Cuisine type
- Restaurant rating

---

## 🔄 Step-by-Step: Combining the Datasets

### ✅ Step 1: Load CSV Data
- Read `orders.csv` using appropriate data loading techniques.

### ✅ Step 2: Load JSON Data
- Load `users.json` to extract user master data.

### ✅ Step 3: Load SQL Data
- Execute SQL queries on `restaurants.sql` to retrieve restaurant information.

### ✅ Step 4: Merge the Data
Datasets are merged using **Left Joins** to retain all order records.

#### 🔑 Join Keys:
- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`

### ✅ Step 5: Create Final Dataset
After merging:
- Order details
- User information
- Restaurant information  
are combined into one dataset.

---

## 📄 Output File

📁 **final_food_delivery_dataset.csv**

This file represents the complete, cleaned, and merged dataset ready for analysis.

---

## 📊 Final Dataset – Learning Objectives

Students are expected to analyze and understand:

### 📈 Order Trends
- Order volume over time
- Seasonal patterns and peak periods

### 👥 User Behavior
- Spending patterns
- Gold vs Regular membership behavior

### 🌍 City-wise Performance
- Revenue contribution by city
- Order distribution across cities

### 🍕 Cuisine-wise Analysis
- Popular cuisines
- Revenue generated per cuisine

### ⭐ Membership Impact
- Revenue contribution from Gold vs Regular members
- Average order value comparison

### 💰 Revenue & Seasonality
- Quarterly and monthly revenue trends
- High-performing periods

---

## 🛠 Technologies Used

- Python
- Pandas
- SQL
- Jupyter Notebook
- CSV & JSON data handling

---

## 🎯 Key Learning Outcomes

By completing this project, students will learn:
- How to work with **multiple data formats**
- How to perform **joins across datasets**
- How to create a **single analytical dataset**
- How to derive **business insights** from raw data

---

## 👨‍🎓 Target Audience

- Data Science students
- Data Analytics learners
- Database and ETL beginners
- Academic project submissions

---

## 📜 License

This project is intended for **educational purposes** only.

---


