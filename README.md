# PHP Product Management Admin Panel

A small PHP and MySQL project demonstrating a basic product-management workflow with a session-based admin area.

## Current Functionality

- User registration and login
- Password hashing and password verification
- Session-based access to the admin area
- Product creation and editing
- Product listing and deletion
- Product fields for title, description, quantity, color, pricing, and status
- Basic user status and role checks

## Technology

- PHP
- MySQL
- MySQLi
- HTML and CSS
- Bootstrap components

## Project Structure

- `Admin.php` — admin dashboard and product listing
- `addproduct.php` — product creation form
- `updateproduct.php` — product editing
- `form.php` — login interface
- `login.php` — login handling
- `registration.php` — user registration
- `logout.php` — session logout

## Setup

1. Install PHP and MySQL using a local development environment such as XAMPP.
2. Clone this repository into the local web server directory.
3. Create a MySQL database and configure the connection in the local connection file.
4. Import the required database tables. The application expects product and registration data.
5. Start Apache and MySQL, then open the project through your local server.

Do not commit database credentials or other secrets.

## Security Note

This is an early-stage PHP project and should be treated as a learning/demo codebase, not a production-ready admin system. Review and improve SQL query parameterization, authorization checks, input validation, CSRF protection, and error handling before using it with real users or data.
