#🛒 Supermart Grocery Sales Analysis
This project analyzes a dataset of retail grocery sales to perform data cleaning, time-based and categorical exploratory data analysis (EDA), and KPI computation to uncover performance trends across categories, cities, and regions.

📌 Project Objective
Clean and preprocess Supermart's retail sales data

Analyze sales trends across time, category, region, and city

Compute key business metrics like total sales, profit, discount impact

Identify top-performing categories, customers, and locations

🧰 Tools & Technologies
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Jupyter Notebook

🧹 Data Cleaning & Preprocessing
Renamed columns and standardized naming conventions

Converted Order Date to datetime format

Extracted Year, Month, and Day Name from order dates

Dropped unused columns like State

📊 Univariate & Time-Based Analysis
Line plot to show monthly sales trend across years

Bar plots to compare sales across categories and subcategories

Pie chart to visualize region-wise sales share

Computed summary stats like total sales, total profit, average discount, and margin

🧾 Category & Region Insights
Top Categories by Sales:

Eggs, Meat & Fish – ₹22.67L

Snacks – ₹22.37L

Food Grains – ₹21.15L

Top Subcategories by Sales:

Health Drinks, Soft Drinks, Cookies

Region Sales:

West – ₹47.98L, East – ₹42.48L, Central – ₹34.68L

North had negligible sales (₹1,254)

🏙️ City & Customer Analysis
Top 5 cities: Kanyakumari, Vellore, Bodi, Tirunelveli, Perambalur

Most frequent customers: Amrish, Krithika, Verma, Arutra, Vidya

📊 KPI Summary
Metric	Value
Total Sales	₹1,49,56,982
Total Profit	₹37,47,121
Average Discount	22.68%
Profit Margin	25.05%

🔍 Key Insights
West and East regions contribute the highest to overall sales

Health drinks and soft drinks are top-selling subcategories

Some cities like Kanyakumari and Vellore drive a large portion of sales

Bakery and Snacks categories have highly profitable orders

North region shows negligible performance and can be excluded from region-based strategy

