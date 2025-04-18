# 🛒 Instacart Customer Behavior Analysis

Exploratory data analysis of a modified Instacart dataset to uncover customer behavior and shopping habits. This project includes data cleaning, visualization, and insights on product preferences, reorder behavior, and peak shopping times.

---

## 📌 Objective

Analyze customer purchase patterns and behavior using a dataset derived from the Instacart grocery delivery platform. The project focuses on answering business-driven questions related to:

- Shopping frequency by day and time
- Reorder rates and first-item patterns
- Product popularity and ordering habits

---

## 📊 Dataset Description

This project uses five modified tables derived from the public Instacart 2017 dataset (originally released on Kaggle). The dataset includes:

1. **orders.csv** – Customer orders with day/time info
2. **products.csv** – Product IDs, names, department and aisle references
3. **order_products.csv** – Ordered items with reordering details
4. **aisles.csv** – Aisle ID-to-name mappings
5. **departments.csv** – Department ID-to-name mappings

Modifications include:
- Reduced file size for performance
- Introduced missing values and duplicates
- Preserved original data distribution

---

## 🔍 Project Workflow

1. **Data Overview**
   - Load and explore each table
   - Understand relationships between them

2. **Data Preprocessing**
   - Handle missing values and duplicates
   - Verify data types and logical consistency

3. **Exploratory Data Analysis**
   - Purchase behavior by hour/day
   - Customer reorder frequency
   - Top reordered and most added-to-cart products
   - Product and user-level reorder proportions

---

## 📊 Key Questions Answered

- What are the busiest hours and days for grocery orders?
- Which products are most frequently ordered and reordered?
- How long do customers typically wait before placing a new order?
- Are there patterns in order size or cart position of certain products?

---

## 📁 Project Structure
