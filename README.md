# Parking Management System

This project is my 12th board exam final project. It is a Parking Management System built using Python and MySQL. The system helps manage vehicles entering and leaving a parking lot by keeping track of the time each vehicle spends inside and calculating the parking fees automatically based on hours parked. All the data is saved securely in a MySQL database so that records can be accessed anytime in the future.

## Technologies Used
- Python (for programming the application logic)
- MySQL (for storing vehicle data and parking details)
- MySQL Connector (to connect Python with MySQL database)

## How It Works
When a vehicle enters, the system records its details and entry time. When it exits, the system calculates the total time parked, computes the parking fee according to an hourly rate, and saves all the information in the database. The system does not delete any records, so you can always check past entries and exits later.

## How to Run This Project
1. Make sure MySQL is installed and running on your computer.
2. Create a database named `parking_management` (or any name you prefer).
3. Create the necessary table(s) to store vehicle information.
4. Install the Python MySQL connector module if you don’t have it already by running:
5. Run the Python program. It will interact with the database to record and manage parking data.
6. Follow the on-screen prompts to enter vehicle details and manage parking operations.

## Features
- Easy to use interface through the Python console
- Automatic calculation of parking fees based on hours parked
- Secure data storage in MySQL for all vehicle entries and exits
- Keeps historical data without deleting previous records

## Why I Built This Project
I wanted to create a practical application that shows how Python can be connected to a database to solve real-life problems. This project helped me understand how to work with databases and apply programming skills in a useful way.

## Author
Mannya Santhosh
