# INVENTORY MANAGEMNET SYSTEM

## How To run

### Step-by-Step Instructions:

1. Clone the repository
* Open a terminal or command prompt on your computer.
* Navigate to the directory where you want to clone the repository.
* Use the git clone command to clone the repository. For example:

```
git clone https://github.com/eisax/inventory-management-system.git
```

* This will create a folder named inventory-management-system containing all the project files.

2. Create database in MySQL
* Open your MySQL client (such as MySQL Workbench, phpMyAdmin, or any other MySQL management tool).
* Log in with your MySQL username and password.
* Create a new database for the inventory management system
* You can use the following SQL command:

```
CREATE DATABASE sms_db;
```

* Replace sms_db with your preferred database name if desired.

3. Import database

* Locate the SQL file provided with the repository, typically named something like sms_db.sql.
* Import this SQL file into your newly created database. If using a command line tool, you can do this with:

```
mysql -u your-username -p sms_db < /path/to/sms_db.sql
```

* If using a GUI tool like phpMyAdmin, navigate to the Import section, choose the sms_db.sql file, and import it.

4. Open the website via an SQL client like XAMPP

* Ensure you have XAMPP installed on your computer. You can download it from Apache Friends.
* Start the Apache and MySQL services from the XAMPP control panel.
* Place the cloned repository folder (e.g., inventory-management-system) in the htdocs directory of your XAMPP installation. The typical path is C:\xampp\htdocs\ on Windows or /Applications/XAMPP/htdocs/ on macOS.
* Open your web browser and navigate to http://localhost/inventory-management-system (or the appropriate path if you renamed the folder).

5. Log In Using the Provided Credentials:

* Once the website loads, you will see a login page.
* Enter the following credentials to log in:
* * Username: admin
* * Password: admin123
* Click the login button to access the inventory management system dashboard.

## Additional Notes:
* Ensure that your MySQL server is running and accessible from the web server.
* If there are any configuration files in the repository (such as config.php), ensure they are properly set up to connect to your MySQL database with the correct credentials.
* If you encounter any errors, check the logs for more details and verify that all services (Apache, MySQL) are running correctly.
* You might need to adjust file permissions on certain directories to ensure the web server can read and write files as needed.

Following these steps should allow you to successfully run the Inventory Management System on your local machine. If you run into any issues, refer to the project's documentation or seek help from the community or project maintainers.