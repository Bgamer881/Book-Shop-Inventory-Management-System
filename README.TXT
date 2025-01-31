# Bookshop Inventory Management System

## Overview
This application provides bookshops with an efficient inventory management system.
Employees can manage books, generate invoices, and track stock levels.
Administrators have additional privileges to oversee users and inventory records.

## Features
- **User Login**: Employees and administrators can log in using a secure username and password system.
  - Displays error messages for incorrect credentials.
  - Grants access to the main interface upon successful login.

- **Inventory Management**:
  - Add, update, view, and delete books from the inventory.
  - Search functionality to find books based on book codes.

- **Invoice Generation**:
  - Generate invoices based on book purchases.
  - Auto-fetch book details using a book code.
  - Calculate total cost, payment, and balance.
  - Print invoices for record-keeping.

- **User Management** (Admin Only):
  - Add or remove users from the system.
  - Securely manage employee accounts.

## Usage
1. **Employee Access**
   - Log in with valid credentials.
   - Add, update, view, and delete books.
   - Generate invoices for book purchases.

2. **Admin Access**
   - Log in with admin credentials.
   - Manage inventory and view stock details.
   - Add or remove users from the system.

## Technologies Used
- **Programming Language**: Java
- **Database**: MySQL
- **Development Environment**: NetBeans
- **Server**: WAMP Server
- **Libraries/Tools**:
  - MySQL Connector J (mysql-connector-j-8.1.0)
  - ICPinst.exe (for installer packaging)
  - Launch4j (for creating executable files)
