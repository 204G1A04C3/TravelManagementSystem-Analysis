# TravelManagementSystem
## Project Overview
The Travel Management System (TMS) is a comprehensive software solution designed to streamline and automate the process of planning, booking, and managing travel arrangements for individuals and organizations. By leveraging modern technology and intuitive user interfaces, the TMS aims to simplify the complexities of travel planning while providing users with greater flexibility, convenience, and control over their itineraries.

# Database Schema
## Tables and Their Contents

- customer_id (INT, Primary Key, Auto Increment): Unique identifier for each customer.
- first_name (VARCHAR(50)): First name of the customer.
- last_name (VARCHAR(50)): Last name of the customer.
- age (INT): Age of the customer.
- gender (ENUM('Male', 'Female')): Gender of the customer.
- email (VARCHAR(100), UNIQUE): Email address of the customer.
- phone (VARCHAR(15)): Contact phone number of the customer.
- Address (VARCHAR(255)): Residential address of the customer.
