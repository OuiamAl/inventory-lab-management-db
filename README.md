# inventory-lab-management-db
A relational database project built using MySQL.

📦 Inventory & Lab Management Database
This project is a MySQL database I built to manage different parts of a lab environment — including inventory, orders, repairs, users, reservations, and schedules.
It represents how a real lab or equipment center would track and organize its items.

🔧 Technologies Used
MySQL

SQL Workbench

ERD design tools

Relational database concepts

Primary & foreign keys

Basic normalization

📚 Project Overview
The goal of this project was to design a clean and structured relational database from scratch.
I created multiple connected tables that represent real processes, such as:

ordering items

storing equipment

tracking repairs

checking out items

managing lab assistant schedules

logging user activity

This helped me understand how large systems organize data and keep everything consistent.

🗂️ Database Structure
The database contains 15+ tables, including:
ORDER, ORDER_ITEM, ITEM, VENDOR, INV_TYPE, LOCATION, STORAGE,
REPAIR, USER, LAB_ASSISTANT, RESERVATION, CHECK_OUT, LOG,
HOURS_WORKED, and WORK_SCHEDULE.

Each table has clear relationships and constraints to ensure the data stays accurate.

🔗 Relationships
Some examples of relationships in the database:

Vendors supply many items

Items can be stored in multiple locations

Orders contain multiple ordered items

Lab assistants have work schedules and logged hours

Repairs are linked to specific items

All relationships use foreign keys to maintain integrity.

📑 Testing the Schema
To verify the structure of each table, I used commands like:

DESCRIBE table_name;


This helped me confirm the columns, data types, and keys were correct.

🛠️ How to Use
Download or clone the repository

Open the SQL file in MySQL Workbench

Run the script to create all tables

Explore the schema using DESCRIBE or ERD tools

✨ Possible Next Steps
Add example data (INSERT statements)

Write sample queries and joins

Add an ERD diagram

Improve the naming conventions

Add triggers or stored procedures

👩‍💻 Author
Ouiam Alkarkari
2nd-year Computer Science Student — Seneca Polytechnic
