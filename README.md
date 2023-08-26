# Alumni Management System

The Alumni Management System is a web-based application designed to manage and maintain alumni data for educational institutions. This README provides step-by-step instructions for setting up the project using XAMPP.

## HackHeros Teams

| Name          | Role          | Background and Role                            |
|---------------|---------------|----------------------------------------|
| Shaikh Mudassir | Team Lead    | B.Tech IT and DB Management Back-End |
| Khan Haris    | Developer     | B.Tech IT and JavaScript Back-End & CSS |
| Kiran Sala    | Developer      | B.Tech IT and DB Connectivity Back-End |
| Dhanush Reddy  | Developer |  B.Tech IT and PHP Back-End |

## Prerequisites

- XAMPP installed on your machine.
- Basic understanding of PHP and MySQL.

## Getting Started

1. **Clone the repository:**
```git clone https://github.com/HackHeros/HackHerosgit```
2. **Navigate to the project directory:**
```cd alumni-management-system```

3. **Database Setup:**
- Open XAMPP and start the Apache and MySQL services.
- Visit `http://localhost/phpmyadmin` in your browser.
- Create a new database named `alumni_db`.
- Import the `alumni_db.sql` file located in the `database` folder to set up the required tables and sample data.

4. **Configure Database Connection:**
- Open the `config.php` file in the `includes` folder.
- Update the database connection settings if necessary:
  ```php
  define('DB_HOST', 'localhost');
  define('DB_USER', 'root');
  define('DB_PASS', '');
  define('DB_NAME', 'alumni_management');
  ```

5. **Start the Application:**
- Copy the entire project folder to the `htdocs` directory of your XAMPP installation (usually located at `C:\xampp\htdocs` on Windows).
- Access the application in your browser: `http://localhost/alumni`.

6. **Login:**
- Use the following default admin credentials to log in:
  - Username: admin
  - Password: admin123

## Features

- Manage alumni profiles.
- View, add, edit, and delete alumni information.
- Search and filter alumni based on various criteria.
- Admin authentication and role-based access.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Description of your changes"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a Pull Request.


---





