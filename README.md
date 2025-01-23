# Cafe Management System

## Overview

This project is a **Cafe Management System**, designed to simplify and manage cafe operations, including menu display, order processing, and category-wise food management. The system is developed using **PHP**, **CSS**, and **MySQL**, and is suitable for deployment in a cafe setting.

## Features

- **Dynamic Menu Management**: Display categories and food items dynamically.
- **Search Functionality**: Allow users to search for food items.
- **Order Processing**: Enable customers to place orders easily.
- **Admin Panel**: Manage categories, food items, and orders.
- **Responsive Design**: User-friendly interface for all devices.

## Folder Structure

```
/cafe_web_prj
|-- .git                    # Git repository data
|-- admin                   # Admin panel files
|-- cafe-management-system  # Core system files
|-- categories.php          # Display categories
|-- category-foods.php      # Display food items by category
|-- css                     # Stylesheets
|-- images                  # Images used in the project
|-- index.php               # Homepage
|-- menu-search.php         # Search menu items
|-- menu.php                # Display menu items
|-- order.php               # Order placement page
|-- partials-front          # Frontend partials (header, footer, etc.)
```

## Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   ```

2. **Set Up the Database**:

   - Create a database (e.g., `cafe_db`).
   - Import the provided SQL file (`cafe-management-system.sql`) into the database.

3. **Configure Database Connection**:

   - Open the `config.php` file in the project directory.
   - Update the database credentials:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "cafe_db";
     ```

4. **Start the Server**:

   - Use **XAMPP** or **WAMP** to host the project.
   - Place the project folder in the `htdocs` directory.
   - Start Apache and MySQL services.

5. **Access the Application**:

   - Open your browser and navigate to:
     ```
     http://localhost/cafe_web_prj
     ```

## Technologies Used

- **Backend**: PHP
- **Frontend**: HTML, CSS
- **Database**: MySQL

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with descriptive messages.
4. Push the changes to your branch.
5. Submit a pull request for review.







