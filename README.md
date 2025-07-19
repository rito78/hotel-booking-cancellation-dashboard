# 🏨 Hotel Booking Cancellation Dashboard using Excel

This project is a comprehensive data analysis and visualization solution built using **Microsoft Excel**. It explores the **patterns, trends, and factors** that influence hotel booking cancellations. The goal is to equip hotel managers, data analysts, and business stakeholders with meaningful insights that can help optimize operations and reduce cancellation rates.

This dashboard was created based on a real-world dataset sourced from **Kaggle**, containing over 119,000 hotel booking records from both city and resort hotels. Through data cleaning, analysis, and Excel-based dashboarding, the project uncovers how variables such as deposit type, lead time, country, and booking source influence cancellation behavior.

---

## 📁 Project Structure

```
Hotel-Booking-Cancellation-Dashboard/
│
├── Hotel Booking Cancellation.xlsx    # Final interactive Excel dashboard
├── hotel_bookings dataset.csv         # Raw dataset from Kaggle
└── README.md                          # Project documentation
```

---

## 🎯 Project Objective

The primary goal of this project is to:

- Analyze hotel booking cancellation patterns  
- Identify key factors driving cancellations  
- Visualize insights in an interactive and intuitive Excel dashboard  
- Enable data-driven decisions for reducing cancellations and improving hotel revenue  

The dashboard provides an easy-to-navigate interface that helps non-technical users explore complex data by slicing through dimensions like **hotel type**, **customer segment**, **seasonality**, and **geography**.

---

## 📊 Dataset Summary

- **Source:** Hotel Booking Demand Dataset – Kaggle  
- **Format:** CSV  
- **Rows:** ~119,000 records  
- **Duration:** July 2015 – August 2017  
- **Hotels:** Two types – City Hotel and Resort Hotel  

### 🧾 Key Features in Dataset:
- `is_canceled`: Booking status  
- `lead_time`: Time between booking and arrival  
- `arrival_date_*`: Booking month, week, day  
- `country`, `customer_type`, `deposit_type`  
- `total_of_special_requests`, `market_segment`

---

## 🧹 Data Cleaning & Preparation

Performed using **Microsoft Excel**, including:

- Removed duplicates and null entries  
- Standardized date columns for time series analysis  
- Created derived fields like cancellation percentage  
- Formatted data for pivot table and slicer use

---

## 📈 Dashboard Highlights

Built entirely using Excel tools including **Pivot Tables**, **Pivot Charts**, **Slicers**, and **Conditional Formatting**, the dashboard includes:

### 📌 Cancellation Rate Analysis by:
- Hotel Type (City vs Resort)  
- Deposit Type (No Deposit, Refundable, Non-refundable)  
- Customer Type (Transient, Group, etc.)  
- Country  

### 📊 Monthly Booking Trends
- Visualizing seasonal peaks and dips in cancellations  

### 📉 Lead Time Impact
- Correlation between lead time and likelihood of cancellations  

### 🌍 Geographic Breakdown
- Country-wise cancellation behavior and trends  


---

## 💡 Key Insights Derived

- **Resort Hotels** have a noticeably higher cancellation rate compared to **City Hotels**  
- **Non-refundable deposits** significantly lower the likelihood of cancellations  
- Customers with **longer lead times** tend to cancel more often  
- **Transient customers** make up the largest portion of bookings but also contribute to a higher share of cancellations  
- Top countries by volume include **Portugal**, **United Kingdom**, and **France**, each exhibiting different cancellation behaviors  

These findings can help hotels:
- Adjust pricing and deposit strategies  
- Reduce cancellations by targeting riskier segments  
- Enhance revenue forecasting accuracy  

---

## 🛠 Tools & Skills Demonstrated

- **Microsoft Excel**
  - Data Cleaning  
  - Pivot Tables and Charts  
  - Conditional Formatting  
  - Data Slicers and Filters  

- **Analytical Thinking**
  - Exploratory Data Analysis (EDA)  
  - Pattern Recognition  
  - Visual Storytelling  

---

