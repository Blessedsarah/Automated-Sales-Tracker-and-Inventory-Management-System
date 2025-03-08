# Automated-Sales-Tracker-and-Inventory-Management-System
# Project Overview
Managing sales and inventory manually can be overwhelming, especially for small businesses. This project is an automated Excel-based Sales Tracker & Inventory Management System built for my business, BOXITBYLOLA (a gifting brand). This system simplifies sales tracking, automates stock updates, and generates real-time insights through a dynamic dashboard.
## Dashboard
![image](https://github.com/user-attachments/assets/963a8a99-feb0-4478-b53c-30a8a12920db)

# Key Features
## Automated Sales & Purchase Entry
This system eliminates manual data entry by automating the sales and purchase recording process.
- **Macros & VBA Automation:** Recorded macros are assigned to the “SUBMIT” buttons, allowing users to enter sales or purchase details once, and the data is automatically recorded in the respective tables. This reduces human error and saves time.

- **Dynamic Data Validation:** Instead of manually searching for products, the system ensures that selecting a Product Category from a dropdown menu dynamically filters and displays only the relevant products under that category.

- **Automated Price Lookup with XLOOKUP:** When a product is selected, its price or cost is automatically retrieved from the product table using the XLOOKUP function, eliminating the need for manual price entry.

- **Real-Time Total Calculation:** Once a user inputs the quantity, the PRODUCT() function instantly calculates the total sales (Quantity × Price) and total cost (Quantity × Price) for each entry, ensuring accuracy without the need for manual computation.

![image](https://github.com/user-attachments/assets/5194b6bb-d63e-47f2-a0d6-2c3fee77ae2b)

## Inventory Management System
The inventory system ensures real-time tracking of stock levels, preventing overstocking or running out of stock.
- **Real-Time Stock Updates with SUMIF():** The system automatically sums up the total purchases and total sales for each product using SUMIF(), giving an accurate count of items in stock at any moment.

- **Stock Level Calculation:** The remaining stock quantity is dynamically calculated using the formula:
Stock = Total Purchases - Total Sales
This ensures the system always reflects the latest stock levels.

- **Automated Stock Alerts with IF():** The system provides clear stock status updates based on remaining inventory levels:
  - In Stock: When the stock level is sufficient.
  - Low Stock: When stock levels drop below a predefined threshold.
  - Out of Stock: When stock is depleted, indicating an urgent need for restocking.

![image](https://github.com/user-attachments/assets/608fac57-8207-4b55-8ed9-30fd94cdd944)

## Interactive Sales Dashboard
A dynamic dashboard built using Pivot Tables and Excel Charts to provide key business insights.
- **Pivot Tables for Summary Analysis:** Data from the sales and purchase tables are summarized into pivot tables, making it easy to analyze trends and performance.

- **Dynamic Data Visualizations:** Interactive charts and graphs help visualize key metrics such as:
  - Sales Trends Over Time
  - Best-Selling Products
  - Inventory Values
  - Profit/Loss

![image](https://github.com/user-attachments/assets/7ecbc532-0046-493f-84e4-c06d19c3ddc0)

# Data Structure & Workflow

The system is structured into different tables to ensure efficient data organization:

| Table Name  | Description |
|-------------|------------|
| **Sales** | Contains all sales transactions with details like date, product, quantity, amount and customer. |
| **Purchase** | Stores all purchase transactions with supplier details and cost price. |
| **Products** | Lists product names, categories, selling prices, and cost prices. |
| **Products Categories** | Lists product categories. |
| **Customers** | Stores customer names and information (randomly generated for privacy). |
| **Vendors** | Contains supplier details (randomly generated for privacy). |
| **Inventory** | Tracks current stock levels, updated automatically based on purchases and sales. |

# Analysis & Key Insights
## Overview
![image](https://github.com/user-attachments/assets/8c6a4253-6ad7-4abf-9a79-a06228554d0c)
- **₦827.0K Total Sales** – This represents the overall revenue generated from all product sales.
   - **36.47% Increase Vs Last Week** – Sales have significantly improved, indicating positive growth.

- **₦346.8K Profit/Loss** – This is the net profit after deducting total costs from sales revenue.

- **₦805.8K Total Cost** – The total expenditure on purchasing stock.

- **₦325.6K Stock Amount** – The total current value of inventory.

- **46 Products** – The total number of distinct products being tracked.

- **38 Customers** – The total number of unique customers who have made purchases.

## Profit Margin
**41.93%** – This indicates a healthy profit margin, meaning the business is maintaining good profitability on products.

![image](https://github.com/user-attachments/assets/a782fccc-3864-40a2-bb46-73053aca3dcb)

## Sales Performance Analysis**
- **Top-Selling Products:** These items are bringing in the most sales.
  
- **Least-Selling Products:** These items are bringing in the least sales.
  
![image](https://github.com/user-attachments/assets/e45aebc3-7f21-4b10-a230-9b9ad36c53b1)


## Sales Channel Performance
A **pie chart analysis** shows which platforms are driving the most sales:

![image](https://github.com/user-attachments/assets/f882d641-592c-4c3c-a276-d50b2425dca7)

### Key Observations:
- **TikTok dominates** as the top-performing sales channel.  

- **Instagram is underperforming**, indicating the need for better engagement strategies on that platform.

 - **Offline sales** are the least performing chaneel, suggesting a weak in-person customer base.  


## Inventory Analysis

![image](https://github.com/user-attachments/assets/d08ccabb-23c7-4350-9241-be9b3608b913)

### Stock Status
- **5 Products are Out of Stock** – The red alert emphasizes the need for urgent restocking.
  
### Inventory Breakdown
**Total Unit Purchased: 335**
- **Total Stock Available: 143** – The number of unsold products.
- **Total Sales: 192** – The number of products sold so far.

**Insight:**  
- The stock-to-sales ratio suggests that **more than half of the inventory is already sold**. 
- **143 units remaining** means there’s still stock available, but some products need urgent replenishment.

### Restock Alert
A section lists **products that need urgent restocking**, including:
- Infuser Bottle
- Matte Flask
- Comb Set
- Hoho Cup
- Hair Clipper
- ... and more

The business should prioritize restocking high-demand products, especially those marked as "Out of Stock."

# How This System Transforms Business Operations  
- **Saves time** by automating repetitive tasks like data entry and calculations.  
- **Provides real-time insights** into sales performance and inventory levels.  
- **Prevents stock issues** by automatically flagging low-stock items.  
- **Improves decision-making** with data-driven insights from the dashboard.  

This all-in-one Excel solution ensures that my business can efficiently track sales, profits, and stock levels with minimal manual effort.

