# ScienceQtech Employee Performance Mapping (SQL Project)

## 📌 Project Overview
This project is part of the Simplilearn SQL Course-End Project. ScienceQtech is a data science startup working across fraud detection, market basket analysis, self-driving systems, supply chain optimization, healthcare analytics, customer sentiment analysis, and drug discovery.

With the annual appraisal cycle approaching, the HR department requires structured reports on employee details, performance ratings, salaries, and project assignments. As a Junior Database Administrator, this project focuses on building a relational database and extracting insights using SQL.

---

## 🎯 Objectives
- Analyze employee performance and ratings  
- Identify maximum, minimum, and average salaries  
- Validate employee roles based on experience  
- Calculate bonuses for appraisal planning  
- Improve query performance using indexing  

---

## 🗂️ Database Schema
**Database Name:** `employee`

### Tables
- **emp_record_table**: Employee details, salary, ratings, manager, and project mapping  
- **proj_table**: Project information including domain, duration, and status  
- **data_science_team**: Employees belonging to the Data Science department  

An ER diagram was created to represent relationships between tables.

---

## ⚙️ Technologies Used
- MySQL  
- MySQL Workbench  
- SQL (DDL, DML, Joins, Subqueries, Window Functions, Procedures, Functions)

---

## ✅ Tasks Implemented
- Database and table creation with constraints  
- Employee department and rating analysis  
- Manager–employee reporting hierarchy  
- UNION queries across departments  
- Window functions for ranking and max ratings  
- Salary aggregation by role, country, and continent  
- Stored procedure for experience-based filtering  
- Stored function to validate job role standards  
- Index creation and execution plan analysis  
- Bonus calculation based on salary and ratings  

---

## 📈 Key Highlights
- Used `DENSE_RANK()` and window functions  
- Implemented stored procedures and functions  
- Optimized queries using indexes  
- Maintained data integrity with foreign keys  

---

## 📁 How to Run
1. Create the database using the SQL script  
2. Import CSV files from the Simplilearn LMS  
3. Execute queries sequentially in MySQL Workbench  

---

## 🏁 Outcome
This project successfully maps employee performance, validates job roles, calculates compensation metrics, and delivers HR-ready insights using structured SQL analysis.
