# Clean Conscience

---
## How to use local server environment for web development

* Window users: https://www.wampserver.com/en/ <br />
* MAC users: https://phpandmysql.com/extras/installing-mamp/

1. Download the respective package from their offical websites.
2. Run the installer and follow the instructions to set up local server envirnoment. 
3. Once installed, start the local server environment. 
4. Place your web files in the designated directory (e.g., 'www' in WampServer or 'htdocs' in MAMP)
5. Access your projects through a web browser at 'http://localhost/' or a specified port.
6. Use tools provided by WampServer or MAMP to manage your MySQL databases, create tables, and perform database-related tasks. 

---
#### Overview

* Server-Side (PHP): Manages business logic and interacts with the database.
* Database (MySQL): Stores information related to customers, laundry requests, price list, etc.
* Frontend (React.js): Provides a user interface for interacting with the system.
* Web Server (WAMP or MAMP): A local development environment that includes Apache, MySQL, and PHP.

---
## How to run the Laundry Management System Project

1. Download the zip file.
2. Extract the file and copy lms folder.
3. Paste inside root directory (e.g., for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html).
4. Open PHPMyAdmin (http://localhost/phpmyadmin).
5. Create a database with name lmsdb.
6. Import lmsdb.sql file (given inside the zip package in sql file folder).
7. Run the script http://localhost/lms (frontend).
8. For admin panel http://localhost/lms/admin (admin panel).

#### Login Management

* Credential for Admin Panel <br />
- Username: admin <br />
- Password: Test@123 <br />

* Credential for User Panel <br />
- Username: amitk@test.com <br />
- Password: Test@123 <br />

* Else: Register as a new user

---

## How to import MySQL lmsdb to WampServer

1. Go to localhost.
2. Select PhpMyAdmin.
3. Enter root for username and login.
4. Click on the toggle menu and select Databases.
5. Type lmsdb and select Create.
6. Select lmsdb database and on the toggle menu, select Import.
7. Make sure the header says Importing into the database “lmsdb”. After confirming, select Choose File.
8. Select lmsdb.sql file.
9. Scroll down and click on Import.
10. On the left menu, you should see the list of following tables when expanding 

---
