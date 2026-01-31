# 📦 FOOD DELIVERY DATA ANALYSIS – HACKATHON SUBMISSION

---

## 📌 PROJECT OVERVIEW

This project focuses on building a complete end-to-end data analytics workflow for a food delivery platform. The objective is to simulate how real-world companies integrate data from multiple sources and convert raw information into business insights. Data is collected from structured and semi-structured formats, combined into a unified dataset, and analyzed to understand performance, user behavior, and revenue patterns.

The final dataset created in this project serves as the single source of truth and forms the foundation for all analytical tasks performed in this hackathon.

---

## 🗂 DATA SOURCES

The project uses three different data sources to replicate a realistic business environment. The orders dataset, provided in CSV format, contains transactional information such as order IDs, users, restaurants, timestamps, and revenue details. The users dataset, stored in JSON format, includes customer profiles and membership information. The restaurant dataset, provided through an SQL script, contains restaurant attributes such as city and cuisine types. Combining these sources allows us to build a complete analytical view of the business.

---

## ⚙️ DATA PROCESSING AND INTEGRATION

The data processing pipeline begins by loading the CSV file into a Pandas DataFrame to access order-level information. Next, the JSON file is parsed and converted into a structured table representing users and their membership categories. The SQL script is executed to create a restaurant table, which is then imported into the analysis environment.

After loading all three datasets, left joins are performed to merge them into a single dataset. The orders table is used as the base, ensuring that all order records are preserved. User information is joined using the user ID, and restaurant details are merged using the restaurant ID. This integration step produces a comprehensive dataset that links orders, customers, and restaurants together.

The final merged dataset is exported as `final_food_delivery_dataset.csv`, which is used for all further analysis.

---

## 📊 ANALYTICAL OBJECTIVES

The analytical phase of the project aims to extract meaningful business insights from the unified dataset. The study examines how order volumes change over time and identifies patterns in customer purchasing behavior. City-level performance is analyzed to understand geographic trends, while cuisine-based analysis highlights food preferences across regions. The impact of membership types, such as Gold and Regular users, is assessed to determine differences in engagement and revenue contribution. Revenue distribution is studied to understand financial performance, and seasonal patterns are explored to detect fluctuations related to time periods or special events.

---

## 🧠 TOOLS AND TECHNOLOGIES

This project is implemented using Python and the Pandas library for data manipulation and analysis. SQL is used to manage relational data, and Jupyter Notebook provides an interactive environment for executing the entire workflow. Data cleaning, transformation, and merging techniques are applied to ensure the dataset is analysis-ready.

---

## 📁 OUTPUT

The primary output of this project is the file `final_food_delivery_dataset.csv`, which contains the fully merged and processed dataset. This file is the foundation for all visualizations, trend analysis, and business insights generated in the notebook.

---

## 🚀 PROJECT OBJECTIVE

The goal of this project is to demonstrate practical skills in data engineering and analytics by handling multi-source data, performing integration, and deriving actionable insights. It reflects real-world industry scenarios where analysts must work with diverse data formats and produce reliable, insight-driven results.
