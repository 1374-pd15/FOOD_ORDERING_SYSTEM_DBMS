
# 🍽️ Online Food Ordering System – DBMS Project (PHP + MySQL)

## 📄 Description
This is a dynamic web-based food ordering system developed in PHP and MySQL. It enables users (customers) to browse restaurants, view menus, place orders, make payments, and track their order status. Admins can manage users, menus, orders, and payments efficiently through a secure backend panel.

## 🎯 Objective
To design and implement a secure and user-friendly online food ordering platform that facilitates seamless interaction between customers and restaurant administrators using a robust database-driven architecture.

## 🧱 Modules Overview

### 1. Database and Utility Setup
- Tables: `users`, `orders`, `menu_items`, `payments`, `order_details`, etc.
- Schema supports all major backend functionalities.
- 📂 *Implementation Path*: `db/food.sql`

### 2. User Management
- Role-based login/signup (Admin & Customer)
- Password hashing and session control
- 📂 *Implementation Path*: `login.php`, `signup.php`, `logout.php`

### 3. Menus and Navigation
- Filtered view by categories/restaurants
- Search food items and add to cart
- 📂 *Implementation Path*: `index.php`, `food-menu.php`, `restaurant.php`

### 4. Customer Operations
- Place orders, view history, make payments
- Track current order status
- 📂 *Implementation Path*: `my-orders.php`, `checkout.php`, `payment.php`

### 5. Admin Operations
- Add/update/delete food items
- Manage user list, payments, and order confirmations
- Generate reports
- 📂 *Implementation Path*: `admin/` folder (e.g., `admin/manage-food.php`, `admin/manage-users.php`)

## 📐 Architecture
The architecture consists of a client-server model:
- Clients (Admin/Customer) interact through the web interface.
- Orders are processed via a PHP backend.
- A central MySQL database handles user data, orders, and payments.
- Refer to the architecture diagram included.

## ✅ Functional Requirements
- User login/logout and registration
- Order placement and payment gateway
- Admin panel with food/user management

## 🚀 Non-Functional Requirements
- Secure role-based access
- Responsive and user-friendly UI
- Optimized SQL schema for performance

## 🛠 Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (XAMPP recommended)

## 🔧 Installation Steps
1. Import `db/food.sql` into your MySQL database.
2. Configure `includes/dbconnection.php` with your DB credentials.
3. Run the project on XAMPP (`htdocs/Online-Food-Ordering-System-in-PHP-main`).
4. Access via browser at `http://localhost/Online-Food-Ordering-System-in-PHP-main`.
