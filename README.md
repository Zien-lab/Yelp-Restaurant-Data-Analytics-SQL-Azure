# 📊 Yelp Restaurant Data Analytics with SQL & Azure

This project leverages Yelp restaurant data to identify **optimal locations, timings, and business types** for setting up a new restaurant. By importing and transforming Yelp data from Kaggle into a cloud SQL environment, the project provides valuable insights for data-driven restaurant market strategy.

## 🚀 Project Overview

- **Objective**: Analyze restaurant business data to determine the right place, time, and type of restaurant to establish for market success.
- **Data Source**: [Yelp Dataset from Kaggle](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset)

## 🧱 Data Engineering & ETL Pipeline

- Imported over **6.5 million Yelp JSON records** into **Azure SQL Database**.
- Designed and normalized the schema into **8 optimized SQL tables** based on **Third Normal Form (3NF)** to ensure data consistency.
- Utilized **Pandas** and **SQLAlchemy** to:
  - Flatten deeply nested JSON attributes.
  - Optimize variable types.
  - Automate batch uploads and transformation pipelines.

> 📉 Achieved **~80% reduction in data redundancy** and identified **top 20.06% most valuable businesses**.

## 🔍 Data Analysis Highlights

Developed complex SQL queries to analyze:
- ✅ Restaurant **categories and business types**.
- 🗣️ **Consumer sentiment** and review patterns.
- ⏰ **Peak operational days and hours** (e.g., **Friday and Saturday, 5 PM to midnight**).
- 🏙️ Performance comparisons across **1,000+ cities**.

### 🔎 Key Insight Example

> Tucson has a **low average rating** (3.74) but a **high volume of reviews** (250k+), indicating **strong demand with quality improvement opportunities**—making it a promising location for launching a new restaurant.

> As a result, we would suggest opening a Mexican cuisine restaurant in Tucson city, which opens for 6 days a week (Tuesday–Sunday), in late evening hours, i.e. 5:00 pm – 3:00 a.m., and the top users can be asked for feedback for a good restaurant.

## 🛠 Tools & Technologies

- **Languages**: Python (Pandas, SQLAlchemy), SQL
- **Cloud**: Microsoft Azure SQL Database
- **Libraries**: Pandas, JSON, SQLAlchemy
- **ETL**: Automated pipeline with batch uploads

