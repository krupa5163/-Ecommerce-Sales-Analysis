# 📊 E-Commerce Sales Analysis Dashboard  
(Pandas + Excel Project)

## 📌 Project Overview
This project demonstrates an **end-to-end data analytics workflow** using **Python (Pandas)** and **Microsoft Excel**.  
Raw e-commerce sales data was cleaned and analyzed using Pandas, and an **interactive Excel dashboard** was created to present key business insights.

The project focuses on understanding **sales performance, customer behavior, product trends, and regional analysis**.

---

## 🛠 Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib  
- **Microsoft Excel**: Pivot Tables, Charts, KPI Cards, Slicers  
- **IDE**: Jupyter Notebook / VS Code  

---

## 📂 Dataset Information
**Dataset Name:** `synthetic_ecommerce_sales_2025.csv`

### Columns
- Order_ID  
- Order_Date  
- Customer_ID  
- Product_Name  
- Category  
- Region  
- Quantity  
- Unit_Price  

---

## 🧹 Data Cleaning (Pandas)
The following data cleaning steps were performed using Pandas:

- Checked and handled missing values  
  - Numerical columns → filled using **median**  
  - Categorical columns → filled using **mode**  
- Removed duplicate records  
- Converted `Order_Date` to datetime format  
- Created derived columns:
  - **Total_Sales = Quantity × Unit_Price**
  - **Month** extracted from Order_Date  

---

## 📊 Data Analysis (Pandas)
Key analyses performed:

- Total revenue calculation  
- Sales by product category  
- Monthly sales trend analysis  
- Top 10 products by revenue  
- Average Order Value (AOV)  
- Identification of high-value orders  

---

## 📈 Data Visualization (Python)
Visualizations created using **Matplotlib**:

- Bar chart: Sales by Category  
- Line chart: Monthly Sales Trend  
- Bar chart: Top 10 Products by Revenue  
- Histogram: Order Value Distribution  
- Scatter plot: Quantity vs Total Sales  

---

## 📊 Excel Dashboard
An interactive **Excel Dashboard** was built using the cleaned dataset.

### 🔹 KPI Cards
- Total Sales  
- Total Orders  
- Total Customers  
- Average Order Value  

### 🔹 Charts
- Sales by Category  
- Sales by Region  
- Monthly Sales Trend  
- Top Products by Revenue  

### 🔹 Slicers
- Category  
- Region  
- Date  

The dashboard allows users to dynamically filter and analyze sales data.

---

## 🧠 Key Business Insights
- Electronics category generates the highest revenue  
- Sales show clear monthly seasonality  
- A small number of products contribute most of the revenue (Pareto Principle)  
- Sales performance varies across regions  

---

## 📁 Project Structure
