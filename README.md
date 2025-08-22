# 🛒 E-commerce Sales Analysis – Python & MySQL Project  

This project combines **Python, MySQL, and Jupyter Notebook** to analyze Ecommerce sales data.  
It loads multiple datasets into MySQL, executes **SQL queries via Python**, and uses **Pandas & Visualization libraries** to extract business insights.  

---

## 📌 Project Objective  

To answer key **business questions** such as:  
- Which cities and states have the most customers?  
- How many orders were placed in specific years/months?  
- What is the revenue distribution across categories and sellers?  
- How do payment methods and installments affect orders?  
- What are the retention, churn, and YoY growth trends?  

---

## 🧰 Tools & Technologies  

- **Language**: Python  
- **Database**: MySQL  
- **Libraries**: pandas, numpy, matplotlib, seaborn, mysql.connector  
- **Environment**: Jupyter Notebook  

---

## 📊 Dataset Overview  

- **Source**: [Kaggle – Target Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)  
- **Tables Used**:  
  - `customers` → Customer demographics (city, state)  
  - `orders` → Order details & purchase timestamps  
  - `products` → Product category & metadata  
  - `sellers` → Seller IDs & info  
  - `geolocation` → Locations of customers/sellers  
  - `order_items` → Order-product mapping  
  - `payments` → Payment methods & installments  

---

## 🔍 Workflow  

1. **Database Connection**  
   - Connected to MySQL `ecommerce` database using `mysql.connector`.  

2. **Data Queries**  
   - Executed **SQL queries** directly from Python to extract:  
     - Unique cities  
     - Orders per year/month  
     - Sales per category & seller  
     - Installment-based payments  
     - State-wise customer counts  

3. **Exploratory Data Analysis (EDA)**  
   - Used Pandas DataFrames for tabular results.  
   - Applied grouping, joins, and aggregations in SQL.  


---

## 📈 Analysis Performed  

### 🔹 Basic Queries  
- Unique cities where customers are located.  
- Orders placed in 2017.  
- Total sales per category.  
- % of orders paid in installments.  
- Customers count per state.  

### 🔹 Intermediate Queries  
- Orders per month in 2018.  
- Avg. products per order by city.  
- Revenue % per category.  
- Correlation between product price & purchase count.  
- Seller revenue ranking.  

### 🔹 Advanced Queries  
- Moving average of order values (per customer).  
- Cumulative monthly sales (per year).  
- Year-over-Year (YoY) growth rate.  
- Customer retention (6-month repurchase).  
- Top 3 customers by yearly spending.  

---

## 📌 Key Findings  

- Orders grew **year-over-year**, showing clear seasonal spikes.  
- A few **product categories dominate total sales**.  
- Seller performance is **skewed**, with top sellers contributing most of the revenue.  
- Many customers prefer **installment payments**.  
- Retention analysis reveals opportunities for **loyalty campaigns**.  
- The **top 3 customers per year** have significant revenue contribution.  

---

## 📍 Conclusion
This project demonstrates how Python + MySQL + Visualization can:
- Automate querying of structured ecommerce datasets.
- Provide business-ready insights into customers, sellers, and sales trends.
- Identify opportunities for customer retention and revenue growth.
- Support data-driven decision-making with clear KPIs and visuals.

