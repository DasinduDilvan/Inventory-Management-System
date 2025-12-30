# Inventory Management System

## Overview

The **Inventory Management System** is a Python-based application built with **Tkinter** for the graphical user interface (GUI) and **MySQL** for database management. The system allows users to efficiently manage their inventory, track product stock, and generate reports using various visualizations. It is designed to streamline the process of adding, updating, and removing inventory items, while also providing real-time updates and analytical insights.

## Features

### 1. **User Interface (UI)**
- **Homepage**: Displays key inventory statistics such as total product count, distinct categories, total price, and more.
- **Inventory Management**: A table that displays and filters products, showing their `Product Name`, `Category`, `Price`, `Quantity`, `Warranty`, and other attributes.
- **Add Item**: A form that allows users to add new items to the inventory, specifying details like `Product Name`, `Category`, `Quantity`, `Price`, `Warranty`, and a product `Description`.
- **Settings Page**: Includes functionality for managing inventory:
  - **Add 1 Item**: Increment the stock of a product.
  - **Sold 1 Item**: Decrease the stock (indicating that a product has been sold).
  - **Delete Item**: Remove a product from the inventory.
- **Charts & Graphs**: Visual representations of the inventory data, such as sales trends, and the most popular products.

### 2. **Database Integration**
- **MySQL Database**: All product data is stored in a MySQL database, ensuring persistent storage of inventory records.
- **Real-Time Data Fetching**: The system dynamically updates and displays data from the database in real time.
- **Search Functionality**: The search bar allows users to filter inventory based on product name or category.

### 3. **Additional Features**
- **Automatic Timestamping**: The system automatically records the date and time when an item is added to the inventory.
- **Product Management**: Users can add, delete, and modify product details directly from the UI, which reflects in the MySQL database.

### 4. **Graphs & Reports**
- **Sales Status**: A line chart displaying the sales trends over time.
- **Top Products**: A bar chart showing the most popular product categories in the inventory.

---

## Requirements

Before running the project, you need to have the following installed:

- **Python 3.x**: Make sure Python 3.x is installed on your machine.
- **Tkinter**: A Python package for creating GUIs (usually comes pre-installed with Python).
- **MySQL**: A relational database management system to store inventory data.
- **MySQL Connector for Python**: The `mysql-connector-python` package is used to interact with the MySQL database.

Install the required Python packages using the following command:

```bash
pip install mysql-connector-python matplotlib
