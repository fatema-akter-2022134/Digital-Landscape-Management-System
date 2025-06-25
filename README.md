# Digital Landscape Management System for Nurani Garden Center

## Overview

This repository contains the source code and documentation for the **Digital Landscape Management System** developed for **Nurani Garden Center** during my undergraduate internship at **MrSocialFly**. The system provides an online platform to manage landscaping services, including plant rentals, appointment scheduling, and user management. It was designed to enhance user experience and streamline business operations by automating administrative tasks.

## Key Features

- **Admin Panel**: Allows administrators to manage users, plants, appointments, and other resources.
- **User Panel**: Allows customers to browse available plants, make rental requests, and schedule appointments.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Database**: Uses MySQL for storing user, appointment, and plant data.
- **Technologies**: 
  - Frontend: HTML, CSS, JavaScript, Bootstrap
  - Backend: PHP, MySQL
  - Server: Local server for testing and development
  
## Technologies Used

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
  - Bootstrap
- **Backend**:
  - PHP
  - MySQL

## Installation Instructions

### Prerequisites

1. **PHP**: Ensure PHP is installed (version 7.4 or higher).
2. **MySQL**: Install MySQL for database management.
3. **Web Server**: Apache or Nginx is recommended.

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/fatema-akter-2022134/Digital-Landscape-Management-System.git
    ```

2. Navigate to the project directory:
    ```bash
    cd digital-landscape-management
    ```

3. Set up the database:
    - Create a new database in MySQL.
    - Import the provided SQL file to set up tables:
      ```bash
      mysql -u username -p database_name < database.sql
      ```

4. Update the configuration file (`config.php`) with your MySQL credentials:
    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'root');
    define('DB_PASSWORD', 'password');
    define('DB_DATABASE', 'nurani_garden');
    ```

5. Set up the server:
    - Place the files on your server's root directory.
    - If using Apache, ensure mod_rewrite is enabled for proper routing.

6. Access the application:
    - Open a web browser and navigate to `http://localhost/Digital-Landscape-Management-System`.

## Usage

### Admin Panel

- Log in using the admin credentials.
- Manage user accounts, products (plants), and appointments.
- Track user interactions and modify system content.

### User Panel

- Browse plant services.
- Book appointments for plant rentals.
- Leave testimonials and contact support.

## Testing

The system has been tested for functionality, performance, and security:

- **User Authentication**: Ensure that both admin and customer login functionalities work correctly.
- **Appointment Scheduling**: Test the booking system and ensure that appointments are correctly stored in the database.
- **Plant Catalog**: Ensure that admins can add, modify, and remove plant listings.

## Lessons Learned

This project allowed me to apply my theoretical knowledge from courses such as **Web Development**, **Database Management**, and **System Design** to a real-world scenario. I learned how to:

- Build a full-stack web application.
- Manage both frontend and backend components.
- Implement user authentication and session management.
- Conduct system testing and troubleshoot issues.

## Future Enhancements

- **Mobile App Integration**: Develop mobile applications for both customers and admins.
- **Advanced Analytics**: Integrate data analytics to track system performance and user activity.
- **Enhanced Security**: Improve data encryption and add more robust security features.

