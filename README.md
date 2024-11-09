 Handyman Services Database Schema

Overview
This repository contains the database schema design for a mobile application that connects handymen with clients in need of various services. The schema was designed to support core functionalities, including service listings, booking management, and user feedback.

## Key Features
- User Management: Allows clients and handymen to register, manage profiles, and authenticate.
- Service Listings: Enables handymen to list their skills and services, making them discoverable to clients.
- Booking System: Facilitates scheduling and tracking of service requests between clients and handymen.
- Feedback and Rating System: Allows clients to leave reviews, ensuring transparency and quality.

## Schema Structure
- Tables:
  - `Users`: Stores information about clients and handymen, including roles and contact details.
  - `Services`: Contains details on available services, descriptions, and handyman profiles.
  - `Bookings`: Manages bookings between clients and handymen, with status updates.
  - `Reviews`: Collects client feedback for quality assurance.
  - `Transactions`: Tracks payments and transaction history for services rendered.

## ER Diagram
(https://github.com/DON1CHRIS/HandyMen-Platform-Database-Schema/blob/main/FIX%20PRO%20DATABSE%20SCHEMA.pdf)

## How to Use
1. Clone the Repository:
   ```bash
   git clone https://github.com/DON1CHRIS/Handyman-Services-Database-Schema.git
   ```
2. Set up the Database:
   - Use SQL scripts in the "https://github.com/DON1CHRIS/HandyMen-Platform-Database-Schema/blob/main/SQL%20Scripts%20for%20the%20database%20schema" file to create tables and relationships in your SQL environment.

## License
This project is open-sourced under the MIT License. Feel free to use and modify it as needed.
