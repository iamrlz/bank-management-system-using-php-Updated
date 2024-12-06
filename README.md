# Bank Management System (Updated)

An enhanced version of the **Bank Management System**, providing core banking functionalities with improved features and additional modules. This system is built using **HTML**, **PHP**, and **MySQL**, and is designed for customers and staff to manage banking operations efficiently.

---

## Features

### New and Updated Features:
- **About Page**: Added an informational page about the system (`about.php`).
- **Password Change**: Customers can update their password securely (`customer_pass_change.php`).
- **Profile Section**: Enhanced customer profile view with more details (`customer_profile_myprofile.php`).
- **File Upload**: Added support for file uploads for additional documents (`upload.php`).

### Existing Features:
#### Customer:
- **Login/Logout**: Secure access to the system (`customer_login.php`, `customer_logout.php`).
- **View Profile**: Check and update account details (`customer_profile.php`).
- **Fund Transfer**: Transfer money securely between accounts (`fund_transfer.php`).
- **Account Statement**: View detailed transaction history (`cust_statement.php`).

#### Staff:
- **Login/Logout**: Staff authentication (`staff_login.php`, `staff_logout.php`).
- **Manage Customers**: Add, update, or delete customer accounts (`delete_customer.php`).
- **Transactions**: View customer transaction history (`view_customer_trans.php`).
- **Activity Monitoring**: Access active customer lists (`active_customers.php`).

---

## Prerequisites
1. **Server Setup**: Install XAMPP, WAMP, or any PHP-compatible server.
2. **Database**: Import the SQL schema from the `DATABASE FILE` into MySQL.

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/iamrlz/bank-management-system-using-php-Updated.git

2. Place the project files in the server's root directory (e.g., htdocs for XAMPP).
3. Start the server and MySQL.
4. Import the database schema:
    - Open PHPMyAdmin.
    - Create a new database (e.g., bank_management).
    - Import the SQL file from the DATABASE FILE directory.
5. Open your browser and navigate to:
    `http://localhost/<project-folder>`

## Repository Links
- Old Repository: [View Current Repository](https://github.com/iamrlz/bank-management-system)
- Current Repository for Updates: [View Updated Repository](https://github.com/iamrlz/bank-management-system-using-php-Updated)

### License
This project is intended for educational purposes. You may extend or modify it as needed. For commercial use, please provide appropriate attribution.
