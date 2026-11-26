# Zepto Grocery SQL Analysis

Analyzed Zepto grocery store data using PostgreSQL to answer real business questions.

## What I did
- Cleaned data - removed items with price = 0
- Converted prices from paise to rupees
- Calculated price per gram for fair comparison

## Business Questions Answered
1. Top 10 best-value products by discount
2. Products with high MRP but out of stock
3. Estimated revenue by product category
4. Products where MRP > 500 and discount < 10%
5. Top 5 categories with highest average discount
6. Price per gram for products over 100g
7. Products grouped by weight (Low, Medium, Bulk)
8. Total inventory weight per category

## Tools Used
- PostgreSQL
- SQL - JOINs, GROUP BY, CASE, Window Functions, CTEs

## Columns:

- sku_id: Unique identifier for each product entry (Synthetic Primary Key)

- name: Product name as it appears on the app

- category: Product category like Fruits, Snacks, Beverages, etc.

- mrp: Maximum Retail Price (originally in paise, converted to ₹)

- discountPercent: Discount applied on MRP

- discountedSellingPrice: Final price after discount (also converted to ₹)

- availableQuantity: Units available in inventory

 - weightInGms: Product weight in grams

- outOfStock: Boolean flag indicating stock availability

- quantity: Number of units per package (mixed with grams for loose produce)

 📊 Business Insights

- Found top 10 best-value products based on discount percentage

- Identified high-MRP products that are currently out of stock

- Estimated potential revenue for each product category

- Filtered expensive products (MRP > ₹500) with minimal discount

- Ranked top 5 categories offering highest average discounts

- Calculated price per gram to identify value-for-money products

- Grouped products based on weight into Low, Medium, and Bulk categories

- Measured total inventory weight per product category

  💼 LinkedIn: https://www.linkedin.com/in/vukosi-chauke-6718ba449/

  Email : vccclint@gmail.com
  
## Files
- Zepto_SQL_Project.sql - All queries

  ## THANKS FOR CHECKING THE PROJECT
