# 💳 Credit Card Transaction & Customer Analysis (Power BI)

This project presents an end-to-end **Power BI analytics dashboard** focused on analyzing **credit card transactions and customer behavior**.  
The dashboard helps understand revenue drivers, customer segments, and transaction trends using clean data modeling and business-focused calculations.

---

## 📊 Project Description

The analysis is divided into two interactive Power BI reports:

### Credit Card Transaction Report
- Overall revenue, interest earned, and transaction volume
- Revenue distribution by:
  - Card category (Blue, Silver, Gold, Platinum)
  - Expenditure type (Bills, Fuel, Grocery, Travel, Entertainment, etc.)
  - Education level
  - Profession
- Quarterly revenue vs transaction count comparison
- Card chip usage analysis (Swipe, Chip, Online)

### Credit Card Customer Report
- Customer demographic analysis
- Revenue breakdown by:
  - Age group
  - Income group
  - Marital status
  - Number of dependents
  - Profession
  - Top-performing states
- Weekly revenue trend analysis
- Customer satisfaction and income overview

---

## 🔑 Key KPIs

- **Total Revenue:** 56.52M  
- **Total Interest Earned:** 7.98M  
- **Total Transaction Amount:** 46M  
- **Total Transaction Count:** 667K  
- **Customer Satisfaction Score:** 3.19  

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed directly in **Power BI (Power Query)**:

- Removed duplicate transaction records
- Handled missing and inconsistent values in:
  - Income
  - Education
  - Profession
  - Dependents
- Standardized categorical columns (card type, income group, age group, states)
- Created derived columns:
  - Age Group
  - Income Group
  - Quarter
- Ensured correct data types for dates, revenue, interest, and transaction amounts

---

## 🧱 Data Modeling

- Implemented a **star schema model**
- Fact Table:
  - Credit Card Transactions
- Dimension Tables:
  - Customers
  - Card Category
  - Date
- Relationships created using:
  - Customer ID
  - Card Category
  - Transaction Date
- Model optimized for accurate aggregation and performance

---

## 📐 Calculations & Measures

Business logic and KPIs were implemented using **DAX**, including:

- Total Revenue
- Total Interest Earned
- Total Transaction Amount
- Total Transaction Count
- Quarterly revenue comparison
- Revenue segmentation by customer and card attributes
- Time-based trend analysis (weekly & quarterly)

DAX functions primarily used:
- `SUM`
- `COUNT`
- `CALCULATE`
- `FILTER`
- `DIVIDE`
- Time intelligence functions

---

## 📈 Key Insights

- **Blue card holders** contribute the highest revenue
- **High-income customers** generate maximum transaction value
- Age group **40–50** shows peak spending behavior
- Businessman and white-collar professionals dominate revenue share
- **Q4** records the highest revenue and transaction activity

---

## 🛠 Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Dashboard Design

---

## 🎯 Objective

- Analyze credit card revenue and customer behavior
- Identify high-value customer segments
- Track transaction trends over time
- Demonstrate practical Power BI, DAX, and data modeling skills

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Use slicers (Quarter, Card Type, Transaction Mode, etc.) to explore insights
<img width="1386" height="727" alt="credit2" src="https://github.com/user-attachments/assets/f675daac-4ccc-490b-99ac-6bedb34fe104" />
<img width="1303" height="706" alt="credit1" src="https://github.com/user-attachments/assets/57143e32-71fd-4297-b377-3d60527f110e" />

---

## 📌 Conclusion

This dashboard provides a comprehensive view of **credit card performance and customer analytics**, enabling data-driven decision-making and business insight generation.

---

⭐ If you like this project, feel free to star the repository.
