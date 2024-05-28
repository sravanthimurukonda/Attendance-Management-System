# Attendance-Management-System

Welcome to the Attendance Management System! This system is designed to streamline and simplify the process of tracking attendance for any organization. Whether you're managing a school, a business, or an event, our system provides an intuitive and efficient way to monitor attendance records.
![image](https://github.com/sravanthimurukonda/Attendance-Management-System/assets/113963634/f996be39-9231-4bdf-8ef7-1600d52c5756)


## Getting Started

To get started with the Attendance Management System, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/attendance-management-system.git
    cd attendance-management-system
    ```

2. **Set Up XAMPP**:
    - Download and install XAMPP from [apachefriends.org](https://www.apachefriends.org/index.html).
    - Start Apache and MySQL from the XAMPP Control Panel.

3. **Configure the Database**:
    - Open phpMyAdmin by navigating to `http://localhost/phpmyadmin`.
    - Create a new database named `attendance_db`.
    - Import the provided SQL schema file to set up the required tables.

4. **Run the Application**:
    - Place the backend and frontend files in the appropriate directories within the XAMPP `htdocs` folder.
    - Access the application via your web browser.

## Installation

Follow these detailed steps to install and run the Attendance Management System on your local machine using XAMPP:

1. **Install Dependencies**:
    - Ensure you have Node.js installed. Install required dependencies for the frontend:
        ```bash
        cd frontend
        npm install
        ```
    - Ensure you have PHP installed. Install required dependencies for the backend (if using Composer for PHP):
        ```bash
        cd backend
        composer install
        ```

2. **Database Setup**:
    - Open phpMyAdmin at `http://localhost/phpmyadmin`.
    - Create a new database:
        ```sql
        CREATE DATABASE attendance_db;
        ```
    - Import the database schema from the `schema.sql` file.

3. **Environment Variables**:
    - Configure your environment variables in the backend:
        - Create a `.env` file in the backend directory:
            ```plaintext
            DB_HOST=localhost
            DB_USER=root
            DB_PASS=
            DB_NAME=attendance_db
            ```

4. **Run the Application**:
    - Place your backend files (PHP) in the `htdocs` directory of XAMPP:
        ```bash
        cp -r backend /path/to/xampp/htdocs/attendance-backend
        ```
    - Place your frontend files (HTML, CSS, JS) in the `htdocs` directory of XAMPP:
        ```bash
        cp -r frontend /path/to/xampp/htdocs/attendance-frontend
        ```
    - Start Apache and MySQL from the XAMPP Control Panel.
    - Access the backend via `http://localhost/attendance-backend`.
    - Access the frontend via `http://localhost/attendance-frontend`.

## Technologies Used

The Attendance Management System is built using the following technologies:

- **Frontend**:
    - React.js (or HTML, CSS, JavaScript)
    - Bootstrap (for responsive design)
    
- **Backend**:
    - PHP with XAMPP (Apache)

- **Database**:
    - MySQL

- **Other Tools**:
    - Git for version control

## Features

The Attendance Management System offers a wide range of features to enhance the user experience and streamline attendance tracking:

1. **User Authentication**:
    - Secure login and registration
    - Role-based access control (Admin, Teacher)

2. **Dashboard**:
    - Overview of attendance statistics
    - Recent activity logs

3. **Attendance Tracking**:
    - Mark attendance manually 

4. **Reports and Analytics**:
    - Generate detailed attendance reports
    - Export reports in various formats (PDF, CSV)

5. **Admin Panel**:
    - Manage users and roles
    - Configure system settings

6. **Teacher Panel**:
    - Manage Students and attendance

## Contributing

We welcome contributions from the community! If you would like to contribute to the project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

