📦 Food Delivery Data Analysis – Hackathon Submission
📌 Project Overview

This project builds a complete data analysis pipeline for a food delivery platform.
Data from CSV, JSON, and SQL sources are combined into one final dataset and analyzed to generate business insights.

The final dataset is used as the single source of truth for all analysis.

🗂 Datasets Used
File	Description
orders.csv	Order-level transaction data
users.json	User profile and membership details
restaurants.sql	Restaurant and cuisine information
⚙️ Data Processing Steps

Load CSV data (Orders)

Load JSON data (Users)

Load SQL data (Restaurants)

Perform Left Joins:

orders.user_id → users.user_id

orders.restaurant_id → restaurants.restaurant_id

Create final dataset → final_food_delivery_dataset.csv

📊 Analysis Performed

The following business insights were generated:

📅 Order trends over time

👤 User behavior patterns

🏙 City-wise performance

🍜 Cuisine-wise performance

🥇 Membership impact (Gold vs Regular users)

💰 Revenue distribution

🌦 Seasonality trends

🧠 Skills & Tools Used

Python

Pandas

SQL

Data Cleaning & Merging

Data Analysis

Jupyter Notebook

📁 Output File

final_food_delivery_dataset.csv — final merged dataset used for all analysis.
