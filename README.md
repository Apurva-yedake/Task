# Hotel Management System
## Table of Contents
- [Setup](#setup)
- [Screenshots](#screenshots)
- [For developer](#for-developer)

## Setup
1. Make sure you have `MySQL` and a web server to run/interpret `PHP` in your system.
2. Clone or download the repo and put it to `xampp/htdocs/` if you're using windows, otherwise check tutorial(s) for your corresponding web server and OS. 
3. Install dependencies for JavaScript, `npm install` and PHP, `composer install`.
4. Create a database named `hotel` and run the script [`hotel.sql`](https://github.com/tramyardg/hotel-mgmt-system/blob/master/hotel.sql) to create tables and populate data. Make sure your configuration matches with [`app/DB.php`](https://github.com/tramyardg/hotel-mgmt-system/blob/master/app/DB.php#L14), otherwise make the desired changes.
5. Run the app.

## Create an account
1. Go to the registration page (register.php) i.e. http://hotel.local/register.php
2. Enter your info.
3. To make an admin account
   - 3.1 go to your hotel database
   - 3.2 select table customer
   - 3.3 select an account
   - 3.4 change the value of isadmin to 1
 

