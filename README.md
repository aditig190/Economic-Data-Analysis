# 📊 Sales Data Analysis & Forecasting

## **Overview**
This project analyzes sales transaction data to uncover trends, customer behavior, and revenue patterns, and then forecasts future sales.  
It is part of an internship project and demonstrates the use of **Python, Pandas, Matplotlib, Seaborn, and ARIMA** for end-to-end business analytics.

---

## **Dataset Description**
The dataset contains **34,867** sales transactions with:
- Date, Year, Month
- Customer demographics (Age, Gender, Country, State)
- Product details (Category, Sub-category)
- Sales metrics (Quantity, Unit Cost, Unit Price, Cost, Revenue)

**Time Range:** 19 months of sales data.

---

## **Project Workflow**
### **Step 1: Data Loading**
- Imported libraries
- Loaded dataset
- Checked structure and initial statistics

### **Step 2: Data Exploration**
- Checked missing values and data types
- Performed descriptive statistics

### **Step 3: Data Cleaning & Preparation**
- Handled missing values
- Corrected data types (e.g., Date, Year)
- Verified cleaned dataset

### **Step 4: Exploratory Data Analysis (EDA)**
- **Revenue Trend Over Time**
- **Top Product Categories**
- **Top Revenue-Generating States**
- **Customer Demographic Insights**
- **Correlation Analysis**

### **Step 5: Time Series Analysis**
- Aggregated monthly revenue
- Applied rolling averages to identify trends
- Seasonal decomposition skipped due to short dataset

### **Step 6: Predictive Modeling**
- Used ARIMA model for 6-month revenue forecast
- Evaluated model performance with Mean Squared Error (MSE)

### **Step 7: Business Insights**
- Identified high-performing products and regions
- Recommended marketing and inventory strategies
- Highlighted limitations and next steps

---

## **Key Graphs & Visuals**
> Save all your notebook charts in a folder called `/images` and link them here.

### **1. Monthly Revenue Trend**
![Monthly Revenue](/Monthly_Revenue.png)

### **2. Top Product Categories**
![Top Products](images/top_products.png)

### **3. Top Revenue-Generating States**
![Top States](images/top_states.png)

### **4. Customer Age Distribution**
![Customer Age](images/customer_age_distribution.png)

### **5. Revenue Forecast (ARIMA)**
![Revenue Forecast](images/revenue_forecast.png)

---

## **Business Insights**
- Revenue shows a consistent upward trend with minor seasonal fluctuations.
- A small set of product categories drives the majority of revenue.
- Certain regions dominate sales; targeted campaigns in underperforming regions could increase revenue.
- Forecast indicates **positive growth** over the next 6 months.

---

## **Tech Stack**
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn  
- **Tools:** Jupyter Notebook, Excel (for initial exploration)  

