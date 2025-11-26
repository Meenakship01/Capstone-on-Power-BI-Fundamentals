### Capstone-on-Power-BI-Fundamentals
## Working on Power BI
📊 Power BI Capstone Project – Data Transformation & Analytics Fundamentals

📝 Overview

This capstone project demonstrates fundamental skills in Power BI, specifically focusing on Power Query transformations, data cleaning, and basic analytical calculations.
The project uses a sales dataset containing columns like tax_included_price, order_quantity, and product_price.

The goal is to apply essential data manipulation operations using Transform, Add Column, and Home ribbon features in Power Query, followed by analytical measures in the report view.


---

⭐ Key Features

🔹 1. Data Cleaning & Preparation

Rounded numeric values to required decimal places

Handled duplicated values

Performed median, average, and count operations

Created new calculated columns (e.g., price + delivery charge)
Used Transform, Home, and Add Column tabs effectively


🔹 2. Power Query Transformations

Round (1 decimal place)

Statistics (Average, Median, Count)

Group By for distinct values

Add Column for mathematical operations (+60 Rs delivery charge)


🔹 3. Analytical Measures in Power BI

Distinct count of entries

Average values

Total row counts

Median of price columns
🛠 Technologies Used

Tool / Technology	Purpose

Power BI Desktop	Data modeling & visualization
Power Query Editor	Data cleaning & transformation
DAX (Optional)	Calculated measures
Excel/CSV Dataset	Source data



---

📂 Project Tasks Summary

Below are the tasks performed in this capstone:

1. Round values in tax_included_price
Using Transform → Round → Round to 1 decimal.

2. Count number of entries in order_quantity

Using Transform → Statistics → Count Values
(or Card visual using COUNT).

3. Create new_price by adding ₹60 delivery charge

Using Add Column → Standard → Add → Enter 60.

4. Average of product_price

Using Transform → Statistics → Average
(or AVERAGE(product_price) in DAX).

5. Distinct count of order_quantity

Using:

Home → Group By (Power Query), OR

Card visual → DISTINCTCOUNT(order_quantity).


6. Average of order_quantity

Using Transform → Statistics → Average.

7 & 8. Median of product_price

Using Transform → Statistics → Median.


---

📘 Conclusion

capstone project strengthens understanding of data transformation fundamentals in Power BI, including:

- Cleaning and shaping data in Power Query

- Performing column-level transformations

- Creating new calculated fields

- Applying statistical operations

- Distinguishing between Transform, Add Column, and Home tab features

- Using analytical measures in Report View





