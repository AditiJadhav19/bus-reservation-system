# Bus Reservation System

## 📌 Overview

The Bus Reservation System is a web-based application designed to manage bus reservations efficiently. It allows administrators to manage buses, schedules, and reservations, while users can book and manage their bus tickets.

## 🔍 Table of Contents

- [📝 Project Summary](#-project-summary)
- [💻 Stack](#-stack)
- [⚙️ Setting Up](#-setting-up)
- [🚀 Run Locally](#-run-locally)
- [📂 Project Structure](#-project-structure)

## 📝 Project Summary

The Bus Reservation System provides the following features:
- Admin panel to manage buses, schedules, drivers, conductors, and feedback.
- User interface for booking bus tickets, viewing schedules, and managing reservations.
- Secure authentication and authorization for admin and user roles.

## 💻 Stack

- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: PHP
- Database: MySQL

## ⚙️ Setting Up

### Prerequisites

- PHP installed
- MySQL installed
- Web server (e.g., Apache) installed

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/bus-reservation-system.git
   ```

2. Navigate to the project directory:
   ```sh
   cd bus-reservation-system
   ```

3. Import the database:
   - Create a database named `bus_reservation` in MySQL.
   - Import the SQL file located at `database/bus_reservation.sql` into the `bus_reservation` database.

4. Configure the database connection:
   - Open `config.php` file.
   - Update the database connection details (host, username, password, database name).

## 🚀 Run Locally

1. Start the web server (e.g., Apache) and ensure PHP and MySQL are running.

2. Open a web browser and navigate to `http://localhost/bus-reservation-system`.

3. You should see the Bus Reservation System homepage.

## 📂 Project Structure

```
bus-reservation-system/
│
├── add_admin.php
├── add_bus_details.php
├── add_bus_schedule.php
├── add_conductor.php
├── add_driver.php
├── addBusFeedback.php
├── config.php
├── index.php
├── login.php
├── register.php
├── view_buses.php
├── view_reservations.php
└── database/
    └── bus_reservation.sql
```