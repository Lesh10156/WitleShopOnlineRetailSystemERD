# 🛒 WitleShop Online Retail System

A relational database design project for **WitleShop (Pty) Ltd**, a South African online retailer selling electronics, clothing, and home appliances.

## 📌 Project Overview
-This project was created to demonstrate my ability to analyse business requirements and convert them into a structured relational database design.

The database manages:

- 👤 Customers and delivery addresses
- 📦 Products, categories, and suppliers
- 🛒 Orders and order items
- 💳 Payments
- 🚚 Deliveries

## 🔗 Key Relationships

- Customer → Orders: **1:M**
- Customer → Addresses: **1:M**
- Category → Products: **1:M**
- Supplier → Products: **1:M**
- Order → Payment: **1:1**
- Order → Delivery: **1:1**
- Orders ↔ Products: **M:N**


## 🎓 Project Objectives

- Identify entities
- Define primary and foreign keys
- Establish relationships and cardinality
- Design a complete **Entity Relationship Diagram (ERD)**
- Apply relational database design principles
