🛒 WitleShop Online Retail System

This is a relational database design project for WitleShop (Pty) Ltd, a South African online retail company selling electronics, clothing, and home appliances.

🚀 Project Purpose

This project was created to demonstrate my ability to analyse business requirements and convert them into a structured relational database design

📋 Business Areas
👤 Customer Management
📦 Product Management
🏷️ Category Management
🏭 Supplier Management
🛒 Order Management
💳 Payment Management
🚚 Delivery Management
📍 Customer Delivery Addresses
🎯 Project Objectives

The database was designed to support:

Customer registration and management
Multiple delivery addresses per customer
Product and inventory management
Product categories
Supplier relationships
Customer orders
Multiple products per order
Order payments
Order deliveries
Delivery tracking
Data integrity through primary and foreign keys
🗄️ Database Design
Main Entities
Entity	Primary Key	Purpose
Customer	CustomerID	Stores customer information
Address	AddressID	Stores customer delivery addresses
Category	CategoryID	Stores product categories
Supplier	SupplierID	Stores supplier information
Product	ProductID	Stores products and stock
Order	OrderID	Stores customer orders
OrderItem	OrderItemID	Resolves the Orders/Products many-to-many relationship
Payment	PaymentID	Stores payment information
Delivery	DeliveryID	Stores delivery information
🛠️ Technologies & Tools
Data Modelling
ERD
Relational Data Modelling
Database Normalisation
Tools
GitHub
Draw.io
🔗 Database Relationships
Customer → Address: One-to-Many (1)
Customer → Order: One-to-Many (1)
Category → Product: One-to-Many (1)
Supplier → Product: One-to-Many (1)
Order → Product: Many-to-Many (M), resolved using OrderItem
Order → Payment: One-to-One (1:1)
Order → Delivery: One-to-One (1:1)
📌 Key Database Concepts

This project demonstrates practical understanding of:

Primary Keys
Foreign Keys
Unique Constraints
Entity Relationship Diagrams
Cardinality
One-to-One Relationships
One-to-Many Relationships
Many-to-Many Relationships
Junction Tables
Relational Database Design
Database Normalisation
Data Integrity
📂 Project Structure
witleshop-online-retail-database/
│
├── README.md
│
├── sql/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   └── business_queries.sql
│
├── docs/
│   └── ERD.md
│
└── images/
    └── witleshop-erd.png
🚀 Project Purpose

This project was created to demonstrate my ability to analyse business requirements and convert them into a structured relational database design.

It forms part of my growing SQL, database development, and data analytics portfolio.
