# Pizza Sales Analysis Dashboard 🍕📊

A complete end-to-end sales analytics project built using Power BI, SQL, and Excel to analyze pizza sales performance, customer ordering behavior, revenue trends, and product performance.

This project transforms raw pizza sales data into actionable business insights through interactive dashboards, KPI tracking, and advanced visual analytics.

---

## 📌 Project Overview

The objective of this project is to analyze pizza sales data and uncover key business insights such as:

- Revenue performance
- Customer ordering patterns
- Best-selling and worst-selling pizzas
- Sales trends by category and size
- Daily and monthly order behavior

The dashboard was designed to help stakeholders make data-driven decisions that can improve sales performance, optimize inventory, and enhance customer satisfaction.

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Initial data cleaning & inspection |
| SQL Server | Data querying & transformation |
| Power BI | Data visualization & dashboard creation |
| DAX | KPI calculations and measures |

### Software Versions
- MS Office / Excel 2021
- MS SQL Server 19.0
- SQL Server Management Studio (SSMS) 19.0
- Power BI June 2023 Version

---

## 📂 Repository Structure

📁 Pizza-Sales-Analysis
│
├── 📄 Problem Statement.pdf    # Business requirements
├── 📄 README.md                # Project documentation
├── 📄 page_1.png               # Project dashboard 1
├── 📄 page_2.png               # Project dashboard 2
├── 📄 page_3.png               # Project model view
├── 📄 pizza.pbix               # Power BI dashboard file
├── 📄 pizza_sales.csv          # dataset


---

## 🎯 Business Problem

The business needed to analyze pizza sales performance using key KPIs and visual dashboards to identify:

- Revenue trends
- Customer purchase behavior
- Product performance
- Peak ordering periods
- Best and worst-selling pizzas

The full project requirements are documented in the included PDF file.

---

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks the following KPIs:

### ✅ Total Revenue
Total income generated from pizza sales.

### ✅ Average Order Value
Average amount spent per order.

### ✅ Total Pizzas Sold
Total quantity of pizzas sold.

### ✅ Total Orders
Total number of customer orders placed.

### ✅ Average Pizzas Per Order
Average number of pizzas purchased in each order.

---

## 📈 Dashboard Visualizations

The dashboard includes the following interactive visuals:

### 📅 Daily Trend for Total Orders
- Bar chart showing order activity across days.

### 📆 Monthly Trend for Total Orders
- Line chart displaying monthly sales patterns.

### 🍕 Sales by Pizza Category
- Pie chart analyzing contribution by pizza category.

### 📏 Sales by Pizza Size
- Pie chart showing customer preference by pizza size.

### 📦 Total Pizzas Sold by Category
- Funnel chart comparing category performance.

### 🏆 Top 5 Best Sellers
Based on:
- Revenue
- Quantity Sold
- Total Orders

### 📉 Bottom 5 Worst Sellers
Based on:
- Revenue
- Quantity Sold
- Total Orders

---

## 🧮 Sample DAX Measures

Total Revenue = SUM(pizza_sales[total_price])

Average Order Value =
DIVIDE([Total Revenue], DISTINCTCOUNT(pizza_sales[order_id]))

Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

Total Pizzas Sold = SUM(pizza_sales[quantity])

Average Pizzas Per Order =
DIVIDE([Total Pizzas Sold], [Total Orders])

---

## 🔍 Key Insights

Some major insights discovered from the analysis include:

- Certain pizza categories contribute significantly more revenue than others.
- Peak ordering periods occur during specific days and hours.
- Large-sized pizzas generate a higher share of revenue.
- A few pizza products consistently outperform others in sales and order volume.
- Some menu items underperform and may require marketing or pricing adjustments.

---

## 📷 Dashboard Preview

Add dashboard screenshots here after uploading them to the repository.

Example:

![Dashboard Preview](images/dashboard.png)

---

## 🚀 How to Use

1. Clone the repository

git clone https://github.com/your-username/pizza-sales-analysis.git

2. Open the .pbix file using Microsoft Power BI

3. Load or refresh the dataset if necessary

4. Explore the interactive dashboard visuals

---

## 📚 Learning Outcomes

Through this project, I improved my skills in:

- Data Cleaning
- Data Modeling
- DAX Calculations
- Business Intelligence
- Dashboard Design
- Data Visualization
- SQL Querying
- KPI Development
- Storytelling with Data

---

## 💡 Future Improvements

Potential enhancements for this project:

- Add predictive sales forecasting
- Deploy dashboard to Power BI Service
- Integrate real-time sales streaming
- Build a web app version using Python/Streamlit
- Add customer segmentation analysis

---

## 👨‍💻 Author

Ndubuisi Chukwu
Data Analyst | Power BI Developer | Aspiring Data Scientist
