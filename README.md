# sql-spacex
SQL-powered analysis of SpaceX launch data using SQLite in a Python environment. Explore payloads, landing outcomes, and booster performance through SQL queries and pandas.

# 🚀 SpaceX Launch SQL Analysis

This project demonstrates SQL-powered exploration of SpaceX launch data using a local SQLite database and Jupyter Notebook. It combines SQL querying with Python's pandas and SQLite to uncover insights into SpaceX’s missions, including launch sites, booster performance, payloads, and landing outcomes.

---

## 📊 Overview

| Attribute     | Details                                 |
|---------------|------------------------------------------|
| Dataset       | SpaceX Launch Dataset (IBM Capstone)     |
| Source        | [CSV Link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/labs/module_2/data/Spacex.csv) |
| Tools         | SQL (via ipython-sql), SQLite, pandas    |
| Environment   | Jupyter Notebook                         |
| Focus         | SQL Queries & Data Analysis              |

---

## ✅ Objectives

- Connect to a SQLite database and load launch data
- Clean and prepare the dataset using pandas
- Create SQL tables and run queries inside Jupyter using `%sql`
- Perform exploratory analysis using SQL:
  - Launch sites
  - Booster versions
  - Payload statistics
  - Landing outcomes
  - Mission trends over time

---

## 🔍 Key Analysis Tasks

| Task | Description |
|------|-------------|
| 📌 Task 1 | List all distinct launch sites |
| 📌 Task 2 | Filter launches starting with "CCA" |
| 📌 Task 3 | Total payload mass by NASA (CRS) |
| 📌 Task 4 | Average payload for F9 v1.1 |
| 📌 Task 5 | First successful ground pad landing date |
| 📌 Task 6 | Boosters with 4000–6000kg payloads & drone ship landings |
| 📌 Task 7 | Count of missions by outcome |
| 📌 Task 8 | Boosters carrying the maximum payload |
| 📌 Task 9 | 2015 landing outcome by month |
| 📌 Task 10 | Landing outcomes between specific dates |

---

## 🧠 Skills Demonstrated

- 🗃️ SQL query writing & filtering  
- 📊 Aggregations, sorting, and conditional grouping  
- 🧩 CASE WHEN logic for labeling and categorization  
- 📆 Date parsing and filtering by time ranges  
- 📓 Jupyter Notebook integration for SQL workflows  
- 🧹 Basic data cleaning and preprocessing with pandas  

## 👤 Author

**Rahul Arya**  
🎓 B.Sc. Physics | 📜 IBM & Stanford ML Certified | 💡 Data Science Enthusiast  
