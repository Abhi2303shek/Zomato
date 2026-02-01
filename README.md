# 🍽️ Zomato Market & Restaurant Analysis

## 📌 Project Overview
This project performs an end-to-end **data cleaning and exploratory analysis** on large-scale restaurant data from **:contentReference[oaicite:0]{index=0}**, covering **123,000+ restaurant records across 50+ cities**.

The analysis focuses on understanding **city-wise restaurant density, pricing behaviour, ratings, cuisine distribution, and online delivery trends**, converting raw marketplace data into **business-relevant insights**.

---

## 🎯 Objectives
- Analyse restaurant distribution across cities
- Study pricing patterns and affordability segments
- Understand the relationship between price and ratings
- Identify popular cuisines by market
- Evaluate online delivery penetration

---

## 🗂 Dataset Description
- Records: **123,000+**
- Coverage: **50+ cities**
- Granularity: **Restaurant-level**
- Key attributes:
  - City
  - Restaurant name
  - Cuisines
  - Average cost for two
  - Ratings
  - Votes
  - Online delivery availability

📌 The dataset enables **market, pricing, and consumer behavior analysis** at scale.

---

## 🛠 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
- **Visualization**
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**

---

## 🔍 Data Understanding & Exploration
- Dataset shape and structure analysis
- City-wise record distribution
- Rating and cost range inspection
- Identification of missing and inconsistent values

---

## 🔧 Data Cleaning & Preparation
Key steps performed:

- Removed duplicate restaurant entries
- Standardised city and cuisine names
- Handled missing ratings and cost values
- Converted pricing columns to numeric format
- Cleaned and split multi-cuisine fields
- Validated rating and vote ranges

---

## 🧠 Feature Engineering
- Price segmentation (budget / mid-range / premium)
- Aggregated restaurant counts by city
- Cuisine frequency analysis
- Rating and vote-based performance indicators
- Online delivery penetration metrics

---

## 📊 Exploratory Data Analysis

### 🔹 City-wise Market Analysis
- Restaurant density by city
- Competitive intensity across cities

### 🔹 Pricing & Affordability Analysis
- Average cost distribution
- Price bands by city
- Pricing vs customer ratings

### 🔹 Cuisine Analysis
- Most popular cuisines across cities
- Cuisine diversity by market

### 🔹 Ratings & Customer Feedback
- Rating distribution
- Vote count vs rating relationship

### 🔹 Online Delivery Trends
- Delivery availability by city
- Delivery penetration across price segments

---

## 📈 Key Insights
- Restaurant density is highly concentrated in a few major cities
- Higher pricing does not always correlate with higher ratings
- Certain cuisines dominate across most cities
- Online delivery adoption varies significantly by market and price segment

---

## 📁 Project Structure

📦 Zomato
┣ 📂 data
┃ ┗ Zomato.csv
┃ ┗ zomato_cleaned.xlsx
┣ 📂 notebooks
┃ ┗ Zomato.ipynb
┃ ┗ Zomato_Visuals.ipynb
┣ 📄 README.md
┣ 📄 requirements.txt
┗ 📄 .gitignore
