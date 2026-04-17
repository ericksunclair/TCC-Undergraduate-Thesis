# 📊 Data Warehouse for Scientific Publications in Medicine

## 📌 Overview

This project presents the design and implementation of a **Data Warehouse** for a dataset of **scientific publications in the medical field**.
The goal is to structure, organize, and analyze large volumes of publication data to extract meaningful insights about research trends, authorship patterns, and thematic distributions.

This work was developed as a **Final Graduation Project (TCC)** in Systems Engineering.

---

## 🎯 Objectives

* Design a **dimensional data model** for scientific publications
* Build an end-to-end **ETL pipeline**
* Store and organize data in a **Data Warehouse environment**
* Perform **exploratory and analytical queries**
* Generate insights about:

  * Publication trends over time
  * Most relevant research topics
  * Prolific authors and collaborations

---

## 🏗️ Architecture

The project follows a classic Data Warehouse architecture:

1. **Data Source**

   * Raw dataset of medical publications

2. **ETL Process**

   * Data cleaning and transformation
   * Normalization and structuring
   * Loading into dimensional tables

3. **Data Warehouse**

   * Fact and dimension tables
   * Optimized for analytical queries

4. **Analytics Layer**

   * Queries and visualizations for insight generation

---

## 🧰 Technologies Used

* **Python** – Data processing and transformation
* **SQL** – Data modeling and querying
* **SQLite / Relational Database** – Data storage
* **ETL Tools** – (dbt, DuckDB, PostgreSQL)
* **Visualization Tools** – (Metabase)

---

## 🧱 Data Model

The Data Warehouse was designed using **dimensional modeling**, including:

* **Fact Table**

  * Publications (metrics such as counts, relationships, etc.)

* **Dimension Tables**

  * Authors
  * Journals
  * Topics
  * Time
  * Institutions

This structure enables efficient analytical queries and scalability.

---

## 🔍 Key Analyses

Some of the analyses performed include:

* 📈 Evolution of publications over time
* 🧠 Most frequent research topics
* 👥 Identification of highly prolific authors
* 🔗 Collaboration patterns between researchers

---

## 📚 Academic Context

This project was developed as part of the Systems Engineering program at **UFMG (Federal University of Minas Gerais)**.

---

## 👤 Author

**Erick Sunclair**

* 💼 [LinkedIn](https://www.linkedin.com/in/erick-sunclair-a59053110/)
* 💻 [GitHub](https://github.com/ericksunclair)

---

## ⭐ Contributions & Feedback

Feel free to explore, suggest improvements, or connect with me!
