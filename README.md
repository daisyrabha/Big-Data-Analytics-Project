# Big-Data-Analytics-Project

# 🛍️ Customer Purchase Pattern Analysis using MapReduce (Excel Simulation)

## 📌 Project Overview

This project simulates the logic of the **MapReduce framework** using **Excel**, applying it to a synthetic **retail transaction dataset**. The goal is to analyze customer purchase behavior, identify top-selling products, calculate revenue by category, and highlight the most frequent buyers.

It demonstrates how Big Data concepts can be applied to practical business scenarios—even without using a distributed computing system.

---

## 🎯 Objectives

- Simulate MapReduce's **Map** and **Reduce** phases manually in Excel
- Derive actionable insights from customer transaction data
- Visualize findings using charts (bar and pie)
- Present a structured report explaining the process and outcomes

---

## 🧾 Dataset Description

The dataset contains 100 rows of simulated transaction records, with the following columns:

- `TransactionID`
- `CustomerID`
- `Product`
- `Category`
- `Quantity`
- `Price`
- `Date`

---

## ⚙️ Methodology

### 🔹 Map Phase
Key-value pairs were generated:
- `Product → Quantity`
- `Category → Revenue (Quantity × Price)`
- `CustomerID → 1` (Frequency count)

### 🔹 Reduce Phase
Using pivot tables, we performed aggregations:
- Total quantity per product
- Total revenue per category
- Purchase frequency per customer

---

## 📊 Visualizations

The following charts were created in Excel:
- **Bar Chart**: Top 5 Products by Quantity Sold
- **Pie Chart**: Revenue by Product Category
- **Bar Chart**: Top 5 Frequent Buyers

---


