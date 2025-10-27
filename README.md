
# Pizza Restaurant SQL Database Project

## 🧾 Overview
This project models the operations of a pizza restaurant using SQL.  
It includes tables for **orders, menu items, recipes, ingredients, inventory, customers, and staff scheduling**.  
The goal is to demonstrate practical SQL skills such as **database design, joins, aggregations, and cost analysis**.

---

## 🗂️ Database Structure - (Pizza Database - Schema.sql)

| Table | Description |
|-------|--------------|
| **orders** | Records each order placed by a customer, including item, quantity, and delivery info |
| **customers** | Stores customer names |
| **address** | Delivery address details for each order |
| **item** | Menu item details (name, price, category, size, SKU) |
| **recipe** | Links menu items to their ingredients and required quantities |
| **ingredient** | Raw materials with cost, weight, and measurement |
| **inventory** | Tracks current stock levels for ingredients |
| **staff / shift / rota** | Manage employee work schedules, shifts, and hourly pay |

---

## 📊 SQL Queries

### Q1 – Customer Orders
Displays order details such as item name, category, price, quantity, order date, and delivery address.
| File | Name |
|-------|--------------|
|**SQL File**| Q1-Customer Orders.sql|
|**Results Table**|Customer Orders.csv|

### Q2 – Ingredient Cost Per Recipe
Calculates how many ingredients are needed based on sales and computes total ingredient cost for each item.
| File | Name |
|-------|--------------|
|**SQL File**|Q2-Ingredient Cost Per Recipe.sql|
|**Results Table**|Ingredient Cost Per Recipe.csv|

### Q3 – Remaining Inventory
Compares ingredient usage from Q2 with available inventory to show remaining stock.
| File | Name |
|-------|--------------|
|**SQL File**|Q3-Remaining Inventory.sql|
|**Results Table**|Remaining Inventory.csv|


### Q4 – Staff Shift Costs
Calculates total working hours and labor cost for each employee per shift.
| File | Name |
|-------|--------------|
|**SQL File**|Q4-Staff Shift Costs.sql|
|**Results Table**|Staff Shift Costs.csv|








