DatNguyenThucShop
A simple fashion e-commerce website built with PHP, MySQL, HTML, CSS, and JavaScript. The project includes customer shopping features and an admin area for store management.
Features
Customer
- Browse and search products by category.
- View product details, prices, and available sizes.
- Add, update, and remove items from the shopping cart.
- Register, log in, and manage account information.
- Apply discount coupons and place orders.
- View order history and submit product reviews.
Admin
- View store statistics on the dashboard.
- Manage products and categories.
- Manage customer accounts and discount coupons.
- View and update orders.
- Manage product reviews.
Technologies
- HTML, CSS, JavaScript
- PHP
- MySQL
- MySQLi
Project Setup
1. Install a local PHP environment such as XAMPP.
2. Copy the project folder into the htdocs directory.
3. Start Apache and MySQL.
4. Create a database and import database/datnguyenthucshop.sql using phpMyAdmin.
5. Update the database settings in config/db.php.
6. Open the project in your browser:
http://localhost/WebBanHang-main/
Project Structure
- admin/ – Admin pages
- api/ – PHP API endpoints
- config/ – Database configuration
- css/ – Stylesheets
- database/ – SQL database file
- images/ – Website images
- js/ – JavaScript files
- uploads/ – Uploaded product images
Notes
Configure your own database credentials before running the project. Remove development credentials and review the administrator setup script before publishing the repository.
