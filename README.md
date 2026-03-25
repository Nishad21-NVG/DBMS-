🚌 DBMS - ONLINE BUS BOOKING SYSTEM
📌 Project Description

The Online Bus Booking System is a Database Management System (DBMS) project designed to simplify and automate the process of booking bus tickets. It allows users to search buses, check availability, and reserve seats, while administrators can manage buses, routes, and bookings efficiently.

🎯 Objectives
To automate bus ticket booking operations
To maintain organized records of buses and passengers
To reduce manual errors and improve efficiency
To provide an easy-to-use interface for users and admins
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js / PHP (optional)
Database: MySQL
Tools: VS Code, MySQL Workbench / XAMPP
✨ Key Features
👤 User Features
User registration and login
Search buses by source and destination
View bus details (timing, fare, availability)
Book tickets
Cancel bookings
View booking history
🛠️ Admin Features
Add, update, and delete bus records
Manage routes and schedules
View all bookings
Manage user data
🗄️ Database Design
📋 Tables
Users
user_id (Primary Key)
name
email
password
Buses
bus_id (Primary Key)
bus_name
source
destination
total_seats
available_seats
Bookings
booking_id (Primary Key)
user_id (Foreign Key)
bus_id (Foreign Key)
booking_date
seats_booked
Payments
payment_id (Primary Key)
booking_id (Foreign Key)
amount
status
🔗 Relationships
One user can make multiple bookings
One bus can have multiple bookings
Each booking is linked to one user and one bus
Each payment is linked to a booking
⚙️ System Workflow
User registers/logs in
Searches for available buses
Selects a bus and books seats
Booking is stored in the database
Admin manages system data
🚀 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/dbms-online-bus-booking-system.git
2️⃣ Setup Database
Open MySQL Workbench / phpMyAdmin
Create database:
CREATE DATABASE bus_booking;
Import the .sql file
3️⃣ Run Project
Open in VS Code
Run using Node.js or XAMPP
📸 Screenshots

(Add your project screenshots here)

📈 Future Enhancements
Online payment integration
Seat selection interface
Email/SMS notifications
Mobile application support
🧪 Testing
Booking functionality tested
Database relationships verified
User input validation performed
👨‍💻 Author

Nishad Ghatage

📄 License

This project is for educational purposes only.
