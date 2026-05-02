# SunCoast Retail Visual Analysis

## Module 11 – Data Visualization with Matplotlib (Python)

---

## Overview
This project is a **data visualization assignment** focused on analyzing **SunCoast Retail performance data** using **Python, pandas, NumPy, and Matplotlib**.

The script generates **synthetic retail sales and customer data** and produces a series of visualizations to explore:
- Sales trends over time
- Performance by location and product category
- Relationships between advertising spend and sales
- Customer demographics and purchase behavior
- Market share and pricing tiers

The emphasis is on **visual storytelling and insight generation** rather than model building.

---

## Technologies Used
- Python 3.x
- pandas
- NumPy
- Matplotlib

---

## Data Description

### Sales Data
Synthetic quarterly sales data is generated for:
- **8 quarters** (Q1 2022 – Q4 2023)
- **4 store locations**: Tampa, Miami, Orlando, Jacksonville
- **5 product categories**:
  - Electronics
  - Clothing
  - Home Goods
  - Sporting Goods
  - Beauty

The data includes:
- Quarter and quarter labels
- Sales values
- Advertising spend
- Sales efficiency metrics

Seasonality is applied:
- Q4 includes a holiday boost
- Q1 includes a post‑holiday dip

---

### Customer Data
Synthetic customer data includes:
- Customer age
- Purchase amount
- Location
- Price tier (Budget, Mid‑range, Premium)

Age distributions vary by location to simulate different customer demographics.

---

## Visualizations Included

### 1. Time Series Analysis
- Quarterly sales trends over time
- Sales comparison across locations by quarter

---

### 2. Product & Category Performance
- Grouped bar charts showing category performance by location
- Stacked bar charts showing sales composition across categories

---

### 3. Advertising Effectiveness
- Scatter plot of advertising spend vs sales
- Line chart showing advertising efficiency over time (sales per dollar spent)

---

### 4. Customer Demographics
- Histograms showing customer age distribution (overall and by location)
- Box plots comparing purchase amounts across age groups

---

### 5. Purchase & Pricing Analysis
- Histogram of purchase amount distribution
- Pie chart showing sales distribution by pricing tier

---

### 6. Market Share Analysis
- Pie charts showing:
  - Market share by product category
  - Sales distribution by store location

---

### 7. Business Dashboard
- A comprehensive multi‑subplot dashboard summarizing key business insights

---

## How to Run
1. Ensure Python 3.x is installed
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib
  
