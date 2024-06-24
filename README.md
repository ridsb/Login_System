# Simple Login System

This is a simple PHP-based login system with signup, login, and logout functionality. It uses MySQL for database management and Bootstrap for front-end styling.

## Features

- **Signup**: Users can create an account by providing a username and password.
- ![image](https://github.com/ridsb/Login_System/assets/108459805/03a45965-6bc6-415f-8848-f0a1079052f7)
- ![image](https://github.com/ridsb/Login_System/assets/108459805/77c213d2-b8cf-442e-b147-b112bb933661)


- **Login**: Existing users can log in with their credentials.
- ![image](https://github.com/ridsb/Login_System/assets/108459805/e92334fd-2a3f-4acf-891a-31c9123b4b39)

- **Logout**: Users can securely log out of their accounts.
- ![image](https://github.com/ridsb/Login_System/assets/108459805/089f50ae-580f-4b7b-bd1e-22ff1d73f198)


## Requirements

- PHP (version 7 or higher)
- MySQL
- Apache server (or any PHP-enabled server like Nginx)

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/simple-login-system.git
   cd simple-login-system
   ```

2. **Database setup:**

   - Create a MySQL database named `login_system` (or any name you prefer).
   - Import the `database.sql` file into your database to create the necessary tables.

     ```bash
     mysql -u username -p login_system < database.sql
     ```

3. **Configuration:**

   - Rename `partials/_dbconnect.example.php` to `partials/_dbconnect.php`.
   - Edit `partials/_dbconnect.php` and update the database connection details (`$servername`, `$username`, `$password`, `$database`) with your MySQL credentials.

4. **Run the application:**

   - Start your PHP server (e.g., Apache).
   - Open your web browser and navigate to `http://localhost/simple-login-system`.

## Usage

- **Signup:** Navigate to the signup page (`signup.php`) and create a new account.
- **Login:** Once signed up, navigate to the login page (`login.php`) to log in using your credentials.
- **Logout:** Click on the "Logout" link in the welcome page (`welcome.php`) to securely log out of the system.


---

### Notes:
- Replace `yourusername` in the clone URL with your GitHub username or the appropriate URL of your repository.
- Ensure that you have PHP and MySQL installed and properly configured on your local environment before setting up the project.
- Modify the README further based on additional features, dependencies, or specific instructions relevant to your project setup.

This README provides a clear guide for users to understand how to set up and use your simple login system project while maintaining security and best practices for sensitive information handling. Adjust it according to your specific project details and requirements.
