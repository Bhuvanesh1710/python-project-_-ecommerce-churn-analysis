# E-Commerce Customer Insights Dashboard

## 📌 Project Overview
This project focuses on analyzing customer behavior, product performance, and sales trends using Python and Power BI.

The goal is to extract meaningful insights from the dataset and build an interactive dashboard to support data-driven decision-making.

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI
- Google Colab / Jupyter Notebook
- CSV Dataset

---

## 📂 Dataset Description
The dataset contains e-commerce transaction data including:

- Customer details (age, gender)
- Product information (category, product name)
- Order details (order date, quantity, unit price)
- Subscription status (active, paused, cancelled)
- Purchase behavior (purchase frequency)

---

## 🔧 Data Preprocessing
- Handled missing values using mean/appropriate methods
- Removed duplicate records
- Converted date columns into proper datetime format
- Created new feature:
  - `total_order_value = unit_price × quantity`
- Cleaned column names and standardized data types

---

## 📊 Exploratory Data Analysis (EDA)
Performed:
- Univariate Analysis (distribution of age, price, etc.)
- Bivariate Analysis (country vs orders, category vs gender)
- Multivariate Analysis (price vs quantity, purchase trends)

Visualizations include:
- Bar Charts
- Pie Charts
- Histogram
- Scatter Plot
- Line Chart

---

## 📈 Power BI Dashboard
An interactive dashboard was created with:

- KPI Cards:
  - Top Performing Country
  - Active Customers
  - Best Selling Category

- Visualizations:
  - Orders by Country
  - Orders by Category
  - Customer Age Distribution
  - Price vs Quantity Analysis
  - Purchase Frequency by Country

- Filters (Slicers):
  - Date
  - Country
  - Category

---

## 🔍 Key Insights
- Germany and the UK are top-performing countries
- Clothing and Electronics are the best-selling categories
- Most customers fall in the mid-age group (30–60)
- Higher product prices tend to reduce purchase frequency
- Customer behavior varies significantly across regions

---

## 💡 Business Recommendations
- Focus marketing on high-performing countries
- Increase inventory in top categories
- Use pricing strategies to improve sales of high-value products
- Implement customer engagement strategies in low-performing regions

---

## 🚀 Future Enhancements
- Automate data processing using Python pipelines
- Add real-time data integration
- Implement predictive models for sales forecasting
- Improve dashboard interactivity with drill-down features

---

## 📁 Project Structure
