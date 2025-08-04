# 🛍️ Fashion Retail Sales Analysis Dashboard

> **A Data Analytics Case Study**  
> Uncovering patterns, trends, and business insights from retail sales data in the fashion industry.

---

## 📌 Project Overview

This project is a comprehensive exploratory data analysis (EDA) and dashboard design case study focused on **fashion retail sales data**.  
Using Python for data preprocessing and Tableau for visual storytelling, I designed a set of dashboards to reveal:

- **Seasonal purchase trends**
- **Day-of-week performance**
- **Category-level insights**
- **Customer purchase behaviors**
- **Time-based moving averages (4- and 8-month trends)**

It serves both as a portfolio showcase and a practical example of how businesses can use data to make smarter decisions.

---

## 🎯 Objective

The goal of this project is to:

- **Identify high-performing periods** (e.g., weekdays, months, seasons)
- Spot **sales slumps** and potential causes
- Recommend **data-driven strategies** for promotions and inventory
- Practice and demonstrate **data storytelling**, from raw data to strategic insight

---

## 📊 Data Description

The dataset contains transaction-level information from a retail fashion business, including:

- `Order Date`
- `Purchase Amount`
- `Product Category`
- `Customer ID`
- `Store Region` (if available)

Each row represents a single customer purchase.

---

## 🔧 Tools & Technologies

| Tool       | Purpose                            |
|------------|-------------------------------------|
| Python 🐍   | Data cleaning & preprocessing       |
| Pandas     | Aggregations and feature creation   |
| Tableau 📈 | Interactive dashboards and charts   |
| Matplotlib / Seaborn | Early-stage visual EDA     |

---

## 🚀 Key Features

### ✅ Weekly Trends Analysis
- Sales volume and revenue grouped by **weekday**
- Identifies peak and off-peak days

### ✅ Seasonal Performance
- Monthly sales aggregation with **4- and 8-month moving averages**
- Detects **long-term trends and seasonality**

### ✅ Category Breakdown
- Performance of different **product categories**
- Helps guide marketing and merchandising decisions

### ✅ Actionable Insights
- Recommends **high-impact weekdays** (e.g., Friday) for flash sales
- Suggests potential **restock cycles** or campaign timings

---

## 📈 Sample Visuals

<img src="assets/seasonal_decomposition_daily.png" alt="Fashion Sales Dashboard" width="800"/>

> **Friday consistently outperforms all other days** in both revenue and transaction count. Promotions could be focused on Thursdays and Fridays to capture momentum.

---

## 🧠 What I Learned

- How to **structure a business-focused dashboard** for retail analytics
- The importance of **data aggregation levels** (e.g., daily vs. weekly vs. monthly)
- How to use **moving averages** to detect macro trends
- How to turn messy data into **clean, insight-rich dashboards**

---

## 🗂 Folder Structure

├── data/
│ └── raw_retail_data.csv
├── notebooks/
│ └── retail_eda.ipynb
├── assets/
│ └── sample_dashboard.png
├── dashboards/
│ └── tableau_public_link.twbx
├── README.md



---

## 📎 How to Reproduce

1. Clone the repository:
```bash
git clone https://github.com/paakaer/fashion-retail-dashboard.git
```
2. Open the Jupyter notebook under /notebooks to follow the data wrangling steps.

3. Open the Tableau .twbx file in Tableau Desktop or view on [Tableau Public](https://public.tableau.com/views/FashionRetailSales_17543152118940/main?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).