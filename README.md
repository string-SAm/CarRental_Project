#CarRental_Project

Online Car Rental Management System

This is a Web based Application developed using PHP as a Host Language. Database for the Application is in "Database" folder. It can be imported to your localhost(phpMyAdmin) or any other servers. Also configure the "connection.php" to set up the necessary connections with the database.

PHP/Mysql

This website has two login categories: The Employee Login and Customer Login. This system is managed by the Employee. The Employee adds cars, add drivers and view bookings. When cars are added, they are added with the price and image of the cars so that users who come online can view the price before making orders.

Customers can create an account and also login to their account to view their bookings and other booking details. Customers can view their car rent history when they login to their account. They can also print the invoice with price details.

Cars for rent are listed on the home page once they are added by the Employer. Cars listed for rent on the home page are displayed with the car image and description of the car.

This system is responsive.

When renting a car by a customer online, she/he chooses the start and the end date, driver and other preference for the car renting.

The customers can return cars when the renting period expires.

The Important links are displayed on the home page. The menus are categorized for easy accessibility.

This Web Application is written in PHP.

Features of the online car rental system in PHP
View all Cars listed on the Site
Rent Cars
Add Cars
Add Drivers
Return Cars
Customers Can view car rent history
View bookings
Customer Login
Logout System
See car images
See listed car Description
Booking Amount
Car rent range selection
Employee login
Script Details
Written in – PHP, HTML, JavaScript
Database – MYSQL
Design – Bootstrap, CSS

Step by step to run the script (installation)
A server is required to run this project. We will be using XAMPP.

For XAMPP

The script is provided below, click on download to start downloading the script.
Go to your download folder in your Pc and extract the source code folder.
Copy the folder you extracted and paste it in (for XAMPP xampp/htdocs, for WAMPP wampp/www, for LAMPP var/www/html) root directory in your pc.
Open your XAMPP Control panel and start Apache and MYSQL.
Creating a database

Open your browser
Go to this path “http://localhost/phpmyadmin/”
Click on New on the left side of the screen.
Create a database named “carrental” (or with any other name you want) and click on create. Read NOTE below first.
Click on the import tab.
Click on browse file and select “carrental.sql” from the DATABASE FILE folder we extracted.

After creating a database

Open a new tab on your browser and go to the path. E.g. “http://localhost/car-rental/”. The home page will be displayed; from there you can browse different cars which are listed on the website for rent when you scroll down.
You can then click on the employee or customer to display the login page.
Login using the details below.

**Customer Login Details**

Username: lucas
Password: password

**Employee Login Details**

Username: harry
Password: password

Username: jenny
Password: jenny

### Screenshots:

> - Landing Page
>   <img src="/Screenshots/index.jpg" width="800" height="450" alt="landing_page"/>

> - Available Cars
>   <img src="/Screenshots/available_cars.png" width="800" height="450" alt="available_cars"/>

> - Add Cars
>   <img src="/Screenshots/add_car.png" width="800" height="700" alt="add_car"/>

> - Booking Confirmation
>   <img src="/Screenshots/booking_confirmation.png" width="800" height="800" alt="booking_confirm"/>

> - Return Car
>   <img src="/Screenshots/return_car.png" width="800" height="450" alt="return_car"/>

> - Booking Summary
>   <img src="/Screenshots/bookings.png" width="800" height="450" alt="booking_summary"/>
