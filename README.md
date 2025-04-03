# Inventory Management System

## 📌 Project Overview
The **Inventory Management System** is a SQL-based database project designed to efficiently manage suppliers, products, stock, customers, and orders. It automates stock updates and purchase order generation using triggers.

## 📂 Database Structure
The project consists of the following tables:

- **SUPPLIER**: Stores supplier details.
- **PRODUCT**: Contains product information linked to suppliers.
- **STOCK**: Manages product stock levels.
- **CUST (Customer)**: Stores customer details.
- **ORDERS**: Manages customer orders.
- **PURCHASE_TABLE**: Stores generated purchase orders when stock is low.

## 🔑 Key Features
- **Automated Purchase Orders**: Triggers generate purchase orders when stock falls below the reorder level.
- **Stock Update Triggers**: Orders automatically update stock levels.
- **Data Integrity**: Implements foreign keys and constraints to maintain data consistency.
- **Category and Price Validation**: Ensures products belong to valid categories and have a positive price.

## 🚀 Triggers Used
1. **AUTO_GEN_PUR_ORDER**: Automatically inserts a purchase order when stock is below the reorder level.
2. **STOCK_UPDATE**: Updates stock levels when an order is placed.

## 📊 Sample Queries
- Insert, update, and delete operations for managing suppliers, products, customers, and orders.
- Query to check stock levels and pending purchase orders.

## 🛠️ Technologies Used
- **SQL Server** for database management
- **Triggers & Constraints** for automation and data integrity
- **Stored Procedures & Functions** for modular database operations

## 📌 Future Improvements
- Add user authentication for secure access.
- Implement a front-end interface for user-friendly management.
- Optimize triggers for handling bulk transactions efficiently.

## 📜 How to Use
1. Clone the repository and execute the SQL scripts in **SQL Server**.
2. Insert initial data for suppliers, products, and customers.
3. Place an order and observe automatic stock updates and purchase order generation.
4. Query tables to monitor inventory levels and pending orders.

## Contact
For any queries, contact me sai.subbu.in@gmail.com

---
**Author:** Sai Subba Rao Mahendrakar  
**Date:** 03 March 2025  


---

✅ **Contributions Welcome!** If you have suggestions or improvements, feel free to open a pull request.

