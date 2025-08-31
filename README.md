# Blinkit Inventory Analysis

This project contains Python scripts and datasets for analyzing Blinkit’s inventory, orders, deliveries, and returns. The analysis helps understand sales trends, order status, returns, and warehouse management.
## Project Structure

Blinkit_Inventory/
├─ blinkit_inventory.py # Main Python script for analysis
├─ Dark_Warehouses.csv # Warehouse data
├─ Delivery.csv # Delivery data
├─ Inventory.csv # Inventory details
├─ Orders.csv # Orders data
├─ Products.csv # Product details
├─ Returns.csv # Returned orders data
└─ README.md # Project documentation


---

## Tools & Libraries
- Python 3.x  
- Pandas (data manipulation)  
- Matplotlib & Seaborn (data visualization)  
---

## Features
- Merge orders with product information for analysis  
- Visualize order status counts and total sales per category  
- Analyze returned orders and revenue lost due to returns  
- Overview of warehouse inventory and delivery performance  
---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/shawrahul876-wq/Blinkit_inventory.git
cd Blinkit_inventory

Install required libraries:
pip install pandas matplotlib seaborn

Run the Python script:
python blinkit_inventory.py
Ensure all CSV files are in the same folder as the Python script.

