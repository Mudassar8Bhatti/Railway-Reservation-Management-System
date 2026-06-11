# Railway Reservation Management System

## Overview

The Railway Reservation Management System is a desktop-based application developed using C# Windows Forms and Oracle Database. The system is designed to automate railway reservation operations, manage passenger records, train information, bookings, and ticket cancellations efficiently.

This project provides a user-friendly interface for railway administration and reservation management while ensuring secure data storage through Oracle Database.

---------------------------------------------------

## Technologies Used

- C#
- Windows Forms (.NET Framework)
- Oracle Database
- Visual Studio
- SQL


---------------------------------------------------

## Features

### User Authentication (Login Form)
- Secure login system for authorized users.
- Prevents unauthorized access to the application.

### Train Master
- Add new train records.
- Update train details.
- Delete train information.
- View available trains.

### Passenger Master
- Manage passenger information.
- Store passenger details securely.
- Update and maintain passenger records.

### Reservation Management
- Create new railway reservations.
- Allocate seats to passengers.
- Store booking information in the database.

### Travel Master
- Manage travel schedules and route details.
- Maintain journey-related information.
- Track train travel data.

### Cancellation Module
- Cancel existing reservations.
- Update database records automatically.
- Maintain cancellation history.

---------------------------------------------------

## Database

Oracle Database is used as the backend database for storing:

- User Information
- Train Records
- Passenger Details
- Reservation Records
- Travel Information
- Cancellation Records


---------------------------------------------------
## Project Structure

RailwayReservationManagementSystem/

├── Forms/

│   ├── LoginForm

│   ├── TrainMaster

│   ├── PassengerMaster

│   ├── Reservation

│   ├── TravelMaster

│   └── CancellationForm

│

├── Database/

│   └── SQL Scripts

│

├── Classes/

│

├── Resources/

│

└── RailwayReservationManagementSystem.sln


---------------------------------------------------

## How to Run

### Step 1
Clone the repository:

```bash
git clone https://github.com/Mudassar8Bhatti/Railway-Reservation-Management-System.git
```

### Step 2
Open the solution file in Visual Studio.

### Step 3
Import the Oracle database tables and SQL scripts.

### Step 4
Update the Oracle connection string according to your local database configuration.

### Step 5
Build and run the project.

----------------------------------------------------

## Future Enhancements

- Online Reservation Support
- Ticket Printing
- Fare Calculation Automation
- User Roles and Permissions
- Reporting and Analytics Dashboard

----------------------------------------------------

## Author

Mudassar Saif

GitHub:
https://github.com/Mudassar8Bhatti

-----------------------------------------------------

## License

This project is developed for educational and learning purposes.