# **Credit_Card_Financial_Dashboard**

## **Objective:**
To develop a comprehensive credit card weekly dashboard that provides insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

---

## **Steps Taken:**

### **1. Project Overview:**
- Understood the problem statement and requirements for the credit card dashboard.

### **2. Data Extraction:**
- Imported data into a SQL database.
- Analyzed and understood the data to ensure it met the project's needs.
- Extracted and imported data into Power BI for further processing and visualization.

### **3. Data Processing & DAX Queries:**

#### **Created New Columns:**
- **Age Group**: Categorized customers into different age ranges.
- **Income Group**: Categorized customers into various income brackets.
- **Revenue**: Calculated total revenue per day.
- **week_num2**: Adjusted the week numbers to ensure they sorted in ascending order.

#### **Created New Measures:**
- **Current Week Revenue**: Calculated the revenue for the current week.
- **Previous Week Revenue**: Calculated the revenue for the previous week.
- **Week-on-Week Revenue Percentage**: Calculated the percentage change in revenue from one week to the next.

### **4. Created Dashboards:**

#### **Credit Card (CC) Transaction Report:**
- **Key Performance Indicators (KPIs)**:
  - Total revenue
  - Total interest
  - Total transaction amount
  - Total transaction count
  
- **Comparative Analysis**: 
  - Compared different credit card types based on total revenue, total interest, and total transaction amount.
  - Compared different quarters for total revenue and total transaction count.

- **Detailed Breakdown**:
  - Total revenue by expenditure type, education level, card use type, card type, and job type.

- **Slicers**:
  - Used slicers for quarter, income group, card category, gender, and week to enable interactive filtering.

#### **Credit Card (CC) Customer Report:**
- **Key KPIs**:
  - Total revenue
  - Total interest
  - Total income
  - Customer Satisfaction Score (CSS)
  
- **Comparative Analysis**:
  - Compared total revenue, total interest, and total income by customer job type.

- **Revenue Breakdown**:
  - Showed revenue by date.
  - Showed total revenue by age, income, marital status, number of dependents, education, and top 10 states.

- **Slicers**:
  - Used slicers for gender, quarter, week, card category, and week for detailed analysis.

---

## **Insights:**
- **Total Revenue**: $55 million
- **Total Interest**: $8 million
- **Total Transaction Amount**: $45 million
- **Gender Breakdown**:
  - Male customers contribute $30 million to the total revenue.
  - Female customers contribute $25 million to the total revenue.
- **Credit Card Type Breakdown**:
  - Blue and Silver credit cards contribute 94.5% of the total revenue.
- **Geographical Breakdown**:
  - Texas (TX), New York (NY), and California (CA) contribute 70.9% to the total revenue.

---

## **Technologies Used:**
- **Power BI**: Data visualization and dashboard creation.
- **SQL**: Data extraction and transformation.
- **DAX**: For advanced data processing and measure creation.
