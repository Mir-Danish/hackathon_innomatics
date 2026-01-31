# 🍔 Food Delivery Data Analysis Project

## 📌 Project Overview
This project focuses on integrating multiple real-world datasets to analyze food delivery trends, customer behavior, restaurant performance, and revenue patterns.

The final dataset was created by merging transactional, user, and restaurant data to generate actionable business insights.

---

## 📂 Dataset Description

The project uses three different data sources:

1️⃣ **orders.csv** – Transactional data containing order details such as order ID, user ID, restaurant ID, order date, and total amount.

2️⃣ **users.json** – User master data including customer name, city, and membership status (Gold / Regular).

3️⃣ **restaurants.sql** – Restaurant master data containing restaurant name, cuisine type, and ratings.

---

## 🔧 Technologies Used
- Python
- Pandas
- SQLite
- Jupyter Notebook

---

## ⚙️ Data Processing Steps

### ✅ Step 1: Load Libraries
```python
import pandas as pd
import sqlite3
