# Grocery Store Management System

## Overview
The **Grocery Store Management System** is a console-based application designed to help store owners and staff manage daily operations efficiently. It tracks inventory, processes sales, manages employees, and calculates finances. The system follows object-oriented programming principles with classes and functions organizing various tasks. There are two primary user roles in the system:

- **Administrator**
- **Staff**

## Key Components

### 1. Validity Class
This helper class normalizes user input, such as converting strings or characters to lowercase. It ensures that input is consistent and case-insensitive, which helps avoid errors when matching item names, staff names, or other identifiers.

### 2. Staff Class
The **Staff Class** is at the core of the store’s operations. It manages inventory, processes transactions, and updates stock levels. Staff can perform the following tasks:

- **Inventory Management**: Add new items, adjust quantities, and display current stock of products.
- **Sales Handling**: Process customer purchases, calculate bills based on selling prices, and update the inventory accordingly.
- **Stock Adjustment**: Track cost price and selling price of items, and make changes to stock quantities.

This class ensures day-to-day operations at the store.

### 3. Admin/Manager Class
The **Admin Class** builds upon the **Staff Class** by adding more administrative functionalities. As the store’s manager, the **Admin** can:

- **Employee Management**: Add new staff, view employee details, and track their leave requests.
- **Financial Monitoring**: Calculate store profits by comparing selling prices and costs, and manage expenditures, including employee salaries.
- **Employee Leave Management**: Approve or deduct salary based on leave requests made by staff.

The **Admin** oversees the store’s operations and finances, making key decisions to maintain profitability.

## How the Program Runs

### Login System
Upon starting the program, users are greeted with a login screen. They can choose between:

- **Admin Login**: Enter username ("grocery") and password ("1234") to access the Admin menu.
- **Staff Login**: Staff members can enter their credentials to access the Staff menu.



## Admin Menu Options

1. **Manage Employees**: Add new staff members or view a list of existing employees.
2. **Track Financial Expenditure**: Calculate the store’s net income by assessing profits from sales and deducting employee salaries and goods costs.
3. **Return to Login**: Log out and return to the login screen.



## Staff Menu Options

When a **Staff** member logs in, they have access to the following features:

1. **Inventory Management**: Staff can:
    - Add new products to the stock.
    - Increase or decrease the quantity of existing items based on sales or restocking.
    - Display current stock and prices.
2. **Sales Processing**: When customers make purchases, staff can input item names and quantities, calculate the total bill, and adjust stock levels accordingly.
3. **Leave Management**: Staff can request leaves, and their salary will be adjusted based on the number of leave days taken.
4. **Return to Login**: Staff can log out and go back to the login screen.



## Detailed Inventory and Sales Management

Within the **Inventory Management** section, staff can perform the following actions:

- **Add New Item**: Add new products by providing item name, cost price, selling price, and quantity.
- **Update Existing Items**: Adjust quantities of existing products by adding more stock or reducing the number of items when sold.
- **View Stock**: Display a list of all items in the store with their current stock and prices.



## Functional Overview

### Admin Responsibilities
- **Employee Management**: The Admin can add or remove employees and monitor their performance and leave.
- **Financial Oversight**: The Admin can calculate profits and expenses, providing an overview of the store’s financial health.
- **Salary and Leave Management**: Admin can approve leave requests and adjust staff salaries accordingly.

### Staff Responsibilities
- **Inventory Control**: Manage stock levels, add new items, and update quantities.
- **Sales Transactions**: Process purchases by customers, generate bills, and adjust inventory.
- **Leave Requests**: Staff can apply for leave, and the system adjusts their pay based on leave taken.



## Leave and Salary Management

The **Leave Management System** allows both Admin and Staff to request, approve, and adjust leaves. Staff members can request leave, which will be deducted from their salary based on the duration. The **Admin** can manage leave records and track salary adjustments accordingly.



## Financial Tracking and Profit Calculation

The **Admin** has access to detailed financial tracking. The system calculates the **net profit** by comparing selling prices against cost prices and adjusting for salaries. This helps to determine the store’s financial status, including net income after accounting for employee expenses.



## Example Use Case

1. **Login Screen**:
    - The user chooses either **Admin Login** or **Staff Login**.
    - Admin uses username "grocery" and password "1234" for access.

2. **Admin Menu**:
    - After login, the Admin can choose to manage employees or calculate the net expenditure by evaluating profits and expenses.

3. **Staff Menu**:
    - Staff can log in and then either manage inventory, process sales, or request leave.

4. **Inventory Management**:
    - Staff can add new items or adjust quantities in the stock based on purchases and sales.

5. **Billing**:
    - During a sale, Staff enters the item and quantity purchased, and the program calculates the total cost while updating stock levels.



## Summary

This **Grocery Store Management System** offers a comprehensive and efficient way to handle daily store operations. Admins have control over employee management, financial monitoring, and leave adjustments, while staff members manage inventory, process sales, and request leave. This simple yet effective system streamlines operations, ensuring the smooth functioning of the store.

