Database Creation:

A new database named 'OnlineStoreDB' is created.
Database Selection:

The 'OnlineStoreDB' database is selected for subsequent queries.
Customer Table Creation:

A 'Customers' table is created to store customer information.
It includes columns for CustomerID, FirstName, LastName, Email (with uniqueness constraint), and RegistrationDate.
Product Table Creation:

A 'Products' table is created to store product information.
It includes columns for ProductID, ProductName, Price, and StockQuantity.
Order Table Creation:

An 'Orders' table is created to store order information.
It includes columns for OrderID, CustomerID (foreign key referencing Customers table), and OrderDate.
Order Details Table Creation:

An 'OrderDetails' table is created to store details of items in each order.
It includes columns for OrderDetailID, OrderID (foreign key referencing Orders table), ProductID (foreign key referencing Products table), Quantity, and TotalPrice.
Sample Data Insertion (Customers Table):

Sample data for customers is inserted into the 'Customers' table, including CustomerID, FirstName, LastName, Email, and RegistrationDate.
Sample Data Insertion (Products Table):

Sample data for products is inserted into the 'Products' table, including ProductID, ProductName, Price, and StockQuantity.
Sample Data Insertion (Orders Table):

Sample data for orders is inserted into the 'Orders' table, including OrderID, CustomerID, and OrderDate.
Sample Data Insertion (OrderDetails Table):

Sample data for order details is inserted into the 'OrderDetails' table, including OrderDetailID, OrderID, ProductID, Quantity, and TotalPrice.
In summary, this SQL script creates a database for an online store, defines tables to store customer information, product details, order information, and order details. It also inserts sample data to demonstrate the structure and functionality of the database.
