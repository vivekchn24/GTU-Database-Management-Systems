# 🗃️ Database Management Systems (DBMS) Lab Practicals – GTU

This repository includes practical assignments completed under the **Database Management Systems (DBMS)** subject as per the **GTU (Gujarat Technological University)** curriculum. All practicals are performed using **MySQL** on a Linux terminal and demonstrate schema design, data manipulation, and complex SQL querying.

--->>

## 📚 Subject Information

- **Subject**: Database Management Systems (DBMS)
- **University**: Gujarat Technological University (GTU)
- **Student**: Vivek Chauhan
- **Environment**: MySQL 5.7/8.0 on Ubuntu Linux

--->>

## ✅ Practicals Covered

### 🔹 Assignment 1 – Database Creation & Table Structures
- Created database `vivek`
- Listed all databases and switched to selected one
- Viewed structure of 12+ tables including:
  - `tblstudent`, `tblfaculty`, `tblsubject`, `tblbranch`
  - `tblexamfees`, `tblstudentresult`, `tblstudentcourses`, etc.
- Demonstrated use of `DESC` and `SHOW TABLES`

--->>

### 🔹 Assignment 2 – Data Insertion and SELECT Queries
- Inserted multiple rows into `tblbranch`, `tblstudent`, and `tblsubject`
- Verified insertions using `SELECT * FROM tablename`
- Showed proper schema normalization and foreign key usage

--->>

### 🔹 Assignment 3 – Retrieval Using SQL Clauses
- Used clauses: `WHERE`, `LIKE`, `ORDER BY`, `IN`, `BETWEEN`
- Filtered students by city, birthdate, name patterns, and more
- Queried with JOINs to relate students and faculty using `BranchID`

--->>

### 🔹 Assignment 4 – Aggregation, Subqueries, and Complex Joins
- Used subqueries in `WHERE` and `FROM` clauses
- Correlated data from `tblstudent`, `tblfaculty`, and `tblsubject`
- Attempted percentile and advanced computations (some incomplete)

--->>

### 🔹 Assignment 5 – Advanced SQL and Subquery Practice
- Explored aggregate functions like `MAX()`, `MIN()`, `AVG()`
- Ran nested subqueries for student and faculty details
- Demonstrated joining and filtering on multiple tables with aliases

--->>

## 📁 Folder Structure 
📦 DBMS-Lab-Practicals-GTU
┣ 📄 assignment1.sql
┣ 📄 assignment2.sql
┣ 📄 assignment3.sql
┣ 📄 assignment4.sql
┣ 📄 assignment5.sql
┗ 📄 README.md


--->>

## 🛠️ Technologies Used

- **Database**: MySQL 5.7 / 8.0
- **OS**: Ubuntu Linux
- **Editor**: MySQL CLI (Terminal)
- **Tools**: SQL queries, data definition and manipulation

--->>

## 📌 Notes

- All table names follow proper naming conventions (`tbl*`)
- ERD (Entity Relationship Diagram) not included but structure is normalized
- Best practices like using primary/foreign keys, indexing, and consistent naming are followed

--->>

💬 *"A database isn't just storage — it's structured information waiting to be explored."*
