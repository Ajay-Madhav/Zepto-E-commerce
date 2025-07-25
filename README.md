# Zepto E-commerce Data Analyst Portfolio Project
This portfolio project for a data analyst is based on a genuine e-commerce inventory dataset collected from Zepto, a rapidly expanding quick-commerce startup in India. The project replicates actual analyst procedures, starting from the exploration of raw data to conducting business-oriented data analysis.
##  Project Overview
The goal is to simulate how actual data analysts in the e-commerce or retail industries work behind the scenes to use SQL to:

✅ Set up a messy, real-world e-commerce inventory database

✅ Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies

✅ Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees

✅ Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue and more
## Dataset Overview
The dataset was sourced from Kaggle and was originally scraped from Zepto’s official product listings. It mimics what you’d typically encounter in a real-world e-commerce inventory system.

Each row represents a unique SKU (Stock Keeping Unit) for a product. Duplicate product names exist because the same product may appear multiple times in different package sizes, weights, discounts, or categories to improve visibility – exactly how real catalog data looks.

🧾 Columns:

sku_id: Unique identifier for each product entry (Synthetic Primary Key)

name: Product name as it appears on the app

category: Product category like Fruits, Snacks, Beverages, etc.

mrp: Maximum Retail Price (originally in paise, converted to ₹)

discountPercent: Discount applied on MRP

discountedSellingPrice: Final price after discount (also converted to ₹)

availableQuantity: Units available in inventory

weightInGms: Product weight in grams

outOfStock: Boolean flag indicating stock availability

quantity: Number of units per package (mixed with grams for loose produce)
## Business Insights

* Found top 10 best-value products based on discount percentage

* Identified high-MRP products that are currently out of stock

* Estimated potential revenue for each product category

* Filtered expensive products (MRP > ₹500) with minimal discount

* Ranked top 5 categories offering highest average discounts

* Calculated price per gram to identify value-for-money products

* Grouped products based on weight into Low, Medium, and Bulk categories

* Measured total inventory weight per product category
