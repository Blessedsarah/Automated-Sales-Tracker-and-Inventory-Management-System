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



