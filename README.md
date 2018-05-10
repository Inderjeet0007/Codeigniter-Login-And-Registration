# Codeigniter-Login-And-Registration

# STEPS 
1. Open /application/config/database.php and edit with your database settings

2. On your database, open a SQL terminal paste this and execute:

3. For the demo purpose, we have to enter some records into the database.

4. Open your config file located in the application>config>config.php change your base url and remove index.php 

5. Now open your autoload file located in the application>config>autoload.php and the code $autoload['libraries'] = array(); replace it with this code $autoload['libraries'] = array('session','database');. 

6. Now open the database file located in the application>config>database.php and enter your hostname, user,password and database according to yours. 'hostname' => 'localhost', 'username' => 'root' , 'password' => ' ' , 'database' => 'ci-login-registration'.

7. Now open your route file located in the application>config>routes.php. Here you can set your default controller which you want to run at the first when the application starts. 

# WORKING
1. Start XAMPP's Apache and SQL.

2. Goto http://localhost/phpmyadmin -> Create a Database named "ci-login-registration" -> import the file "ci-login-registration.sql".

2. Goto http://localhost/codeigniter-login-registration/ (PORT No. 8080).

3. The registration page would open up, enter your details and press "register".

4. Use the login page to login your self.

5. Your details will be displayed on the screen with a LOGOUT button.
