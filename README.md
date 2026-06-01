# E-Commerce Interaction Analysis

## Project Overview

This project analyzes e-commerce customer interactions to identify engagement patterns, interaction trends, and customer behavior over time. Using Python, Pandas, and Tableau, the project transforms raw interaction data into actionable insights through data cleaning, exploratory analysis, and dashboard development.

---

## Business Objective

Understanding customer interactions is essential for improving engagement and increasing conversions. This project examines user actions such as likes, views, and purchases to uncover patterns that can support business decision-making.

---

## Dataset Information

The dataset contains customer interaction records with the following fields:

* User ID
* Product ID
* Interaction Type
* Timestamp

Interaction Types:

* Like
* View
* Purchase

---

## Tools Used

* Python
* Pandas
* Jupyter Notebook / Kaggle
* Tableau Public
* GitHub

---

## Data Cleaning Process

The raw dataset required several preprocessing steps before analysis:

### Cleaning Steps

1. Removed completely empty columns
2. Identified and removed 294 duplicate records
3. Removed rows containing missing values
4. Converted timestamp fields to datetime format
5. Validated interaction categories
6. Prepared a cleaned dataset for analysis and visualization

### Final Dataset

* Original Records: 3,294
* Cleaned Records: 2,871
* Final Columns: 4

---

## Exploratory Data Analysis (EDA)

The analysis focused on:

* Distribution of interaction types
* Monthly interaction trends
* Customer activity patterns
* Purchase, view, and like behavior over time

### Interaction Summary

| Interaction Type | Count |
| ---------------- | ----- |
| Like             | 1,145 |
| View             | 871   |
| Purchase         | 855   |

---

## Tableau Dashboard

The interactive dashboard provides:

### Key Performance Indicators (KPIs)

* Total Interactions
* Total Likes
* Total Views
* Total Purchases

### Visualizations

* Monthly Interaction Trend
* Interaction Type Breakdown
* Monthly Interaction Distribution
* Interactive Filters

---

## Key Insights

* Likes represented the largest interaction category.
* User activity increased significantly during October, November, and December.
* Purchases accounted for a substantial share of overall interactions.
* Customer engagement was concentrated during the final quarter of the year.

---

## Project Structure

E-Commerce-Interaction-Analysis/

├── data/

├── images/

├── notebooks/

├── README.md

└── requirements.txt

---

## Dashboard

Tableau Public Dashboard:

(https://public.tableau.com/views/E-CommerceInteractionAnalysisDashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

---

## Author

Gabriel Medina

Aspiring Data Analyst | SQL | Python | Pandas | Tableau
