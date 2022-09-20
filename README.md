# Xenonstack_Project
To run this project, Follow the given steps:
1)First, you have to log in to PHPMyAdmin. Next, click on the Database tab to create a new database.
Enter your database name and click on create database button. As soon as PHPMyAdmin will create a new database.

2)Once you create a database, the second step to creating a user table. The user’s table will have the following fields:

id – int(11)
username  – varchar(100)
email  – varchar(100)
password  – varchar(100)
create_datetime – datetime

3)After creating the table, we have to create a PHP MySQL connector script to connect to the MySQL database server.
Create a file named db.php

4)Next, we have to create a session for the user. Create a file named auth_session.php

5)Furthermore, create PHP file registration.php 
that will create an HTML form. It will allow users to register.

6)Similarly, create a PHP file login.php 
This file code contains a form that allows users to enter username and password.

7)Once user login we will redirect to the user dashboard page. Create a PHP file named dashboard.php
After the user login, you will see the following user dashboard screen.
![image](https://user-images.githubusercontent.com/70309674/191294073-2a48e2d4-8bd3-4dca-81a7-aa494b4239d6.png)


8)When clicking on the logout button we have to destroy user sessions. It will redirect to the login page.
Thus, create a file named logout.php

9)Finally, important step for a user experience perspective. Create CSS file style.css
