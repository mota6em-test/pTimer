iKarRental - PHP Car Rental System

Project Overview

iKarRental is a simple car rental web application built in PHP. It allows users to browse available cars, register, and book vehicles for specific time periods. Administrators can manage cars, reservations, and user accounts.

Features

User Features:

Browse available cars without logging in.

Register and log in to book vehicles.

Filter cars based on:

Availability (specific date range)

Transmission type (Automatic/Manual)

Seating capacity

Daily rental price range

View detailed car pages with images and specifications.

Book available cars for a specific date range.

View booking confirmation or failure messages.

Access personal profile to see booking history.

Logout functionality.

Admin Features:

Separate admin login.

Manage all bookings via admin profile.

Add, edit, or delete car listings.

Modify car details and remove bookings.

Tech Stack

Backend: PHP (without frameworks)

Frontend: HTML, CSS (Bootstrap allowed)

Database: MySQL

Installation Guide

Clone the repository:

git clone https://github.com/yourusername/iKarRental.git
cd iKarRental

Set up a local server (e.g., XAMPP, MAMP, or WAMP).

Create a MySQL database and import database.sql from the project folder.

Update the config.php file with your database credentials.

Start your local server and navigate to:

http://localhost/iKarRental

Database Schema

Cars Table (cars)

Column

Type

id

INT (PK)

brand

VARCHAR

model

VARCHAR

year

INT

transmission

VARCHAR

fuel_type

VARCHAR

passengers

INT

daily_price_huf

INT

image

TEXT

Users Table (users)

Column

Type

id

INT (PK)

name

VARCHAR

email

VARCHAR (Unique)

password

VARCHAR

is_admin

BOOLEAN

Bookings Table (bookings)

Column

Type

id

INT (PK)

car_id

INT (FK)

user_email

VARCHAR (FK)

start_date

DATE

end_date

DATE

Usage Instructions

User Registration/Login: Users must register before booking a car.

Booking a Car: Select available dates and confirm booking.

Admin Access: Log in as admin to add/edit/delete cars and manage bookings.

Known Issues & Future Improvements

Add email notifications for booking confirmations.

Implement a payment system.

Improve UI responsiveness.

Author

Developed by Your Name for a university project.

License

This project is for educational purposes and is not intended for commercial use.
