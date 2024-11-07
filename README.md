# TrendKart

## Project Overview

TrendKart is an e-commerce database management system designed to manage an online marketplace. This project simulates essential functionalities such as managing customers, products, orders, and inventory. The project is built using **DBMS** concepts to ensure efficient storage, retrieval, and manipulation of data.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Schema](#database-schema)
- [Installation Instructions](#installation-instructions)
- [How to Use](#how-to-use)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)

## Features

- **Customer Management**: Register, update, and delete customer profiles.
- **Product Management**: Add, update, and delete product listings.
- **Order Management**: Place, modify, and track orders.
- **Inventory Management**: Track stock levels and update inventory.
- **Report Generation**: Generate sales reports and customer activity summaries.

## Technologies Used

- **Database**: MySQL / PostgreSQL / Oracle / (Specify your DBMS)
- **Backend**: SQL for database queries
- **Frontend (Optional)**: If you have a user interface, mention any UI frameworks (e.g., HTML, CSS, JavaScript)
- **Tools**: ER diagrams, SQL Workbench, or any other tools you have used.

## Database Schema

The database schema for TrendKart consists of the following main tables:

1. **Customers**: Stores customer information (CustomerID, Name, Email, etc.)
2. **Products**: Stores product details (ProductID, Name, Price, Stock, etc.)
3. **Orders**: Stores order details (OrderID, CustomerID, OrderDate, etc.)
4. **Order_Items**: Stores information about products in each order (OrderID, ProductID, Quantity)
5. **Inventory**: Manages stock levels for each product (ProductID, Stock)

## Installation Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/trendkart-dbms.git

2.Import the database schema:
Using MySQL, you can run the following:
SOURCE path_to_your_database_schema.sql;
Set up database configurations in your application (if necessary):

3.Update the DBMS connection parameters such as host, username, password in your codebase.
4.Run the project (depending on whether you have a backend, UI, or just a SQL-based interface).

## How to Use
1. Clone the repository
First, clone the repository to your local machine:
git clone https://github.com/yourusername/trendkart.git
cd trendkart
2. Install Dependencies
Make sure you have all the dependencies installed. If this project uses a package manager like npm, pip, or composer, run:
# for Node.js projects
npm install

# for Python projects
pip install -r requirements.txt
3. Configure Database
Update the database configuration in the project. Open the config.js/settings.py file and set your database credentials:
// for JavaScript/Node.js example
const db = mysql.createConnection({
    host: 'localhost',
    user: 'root',
    password: 'yourpassword',
    database: 'trendkart_db'
});

# for Python example
DATABASE = {
    'name': 'trendkart_db',
    'user': 'root',
    'password': 'yourpassword',
    'host': 'localhost',
    'port': 3306,
}
4. Run the Project
Start your server:
# for Node.js
npm start

# for Python
python app.py
5. Access the Application
Once the server is running, open a browser and navigate to:
http://localhost:3000

## Future Enhancements
*Implement product recommendations using machine learning.
*Add an admin panel for product management.
*Improve the UI/UX with a modern design.
*Integrate payment gateways.

## Contributors
*Name:Vaishnavi B
*LinkedIn:https://www.linkedin.com/in/vaishnavi-b-770b8a25b




