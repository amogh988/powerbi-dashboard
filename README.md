

📊 Blinkit Sales Analysis Dashboard (Power BI)

 📌 Project Overview

This project presents an interactive **Power BI dashboard** built using the Blinkit sales dataset. The goal is to analyze sales performance, customer preferences, and outlet-level insights to support better business decisions.


 🎯 Objectives

* Analyze overall **sales performance**
* Understand **customer buying patterns**
* Compare **outlet types and sizes**
* Evaluate **product categories and fat content trends**
* Track **ratings and customer satisfaction**


📈 Key Metrics (KPIs)

* **Total Sales:** 1.20M
* **Average Sales:** 140.99
* **Number of Items:** 9K
* **Average Rating:** 3.92


📊 Dashboard Features

 1. Sales Analysis

* Total sales distribution across **item types**
* Comparison of **high-performing vs low-performing categories**

2. Outlet Insights

* Sales by **Outlet Size (Small, Medium, High)**
* Sales by **Outlet Type (Grocery Store, Supermarkets)**
* Sales trend based on **Outlet Establishment Year**

 3. Product Insights

* Sales by **Item Fat Content (Low Fat, Regular, etc.)**
* Identification of **top-selling product categories**

 4. Customer Feedback

* Analysis of **average ratings across outlet types**
* Correlation between **sales and ratings**

 5. Filters & Interactivity

* Outlet Location Type
* Outlet Size
* Item Type
* Dynamic filtering for better data exploration


 🔍 Key Insights

* **Low Fat products contribute the highest sales share (~60%)**, indicating health-conscious customer behavior.
* **Tier 3 outlets generate the highest sales**, showing strong demand in smaller cities.
* **Supermarket Type 1 dominates in both sales and item count**, making it the most impactful outlet type.
* Sales peaked around certain establishment years, suggesting **mature outlets perform better**.
* Ratings remain consistent (~3.9), indicating **stable customer satisfaction** across outlets.

🛠 Tools & Technologies

* **Power BI** – Dashboard creation & visualization
* **DAX (Data Analysis Expressions)** – Measures and calculations
* **Excel / CSV Dataset** – Data source



### 🧮 DAX Measures Used

* Total Sales = `SUM(Sales)`
* Number of Items = `COUNT(Item ID)`
* Average Sales = `AVERAGE(Sales)`
* Average Rating = `AVERAGE(Rating)`

 📂 Dataset Description

The dataset includes:

* Item Type
* Fat Content
* Outlet Type & Size
* Outlet Establishment Year
* Sales & Rating

🚀 Conclusion

This dashboard helps stakeholders quickly understand sales trends, identify top-performing outlets, and make data-driven decisions to improve business performance.
