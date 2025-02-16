# Flight Booking System

Description

The Flight Booking System is a web-based application built using Spring Boot (backend) and React (frontend). It allows users to search for flights, book tickets, manage reservations, and process payments. The system is designed for airlines and travel agencies to provide a seamless flight booking experience for customers.

Features

User Authentication (Sign Up, Login, Password Reset)

Flight Search & Filters (By Date, Destination, Price, Airline)

Real-time Seat Availability Check

Online Booking & Ticket Generation

Payment Gateway Integration (Stripe/PayPal)

Admin Dashboard for Managing Flights & Bookings

Email Notifications (Booking Confirmation, Cancellation Alerts)

User Profile Management (View & Manage Bookings)

RESTful API for Data Handling

Technologies Used

Backend (Spring Boot)

Spring Boot (Java)

Spring Security (JWT Authentication)

Spring Data JPA (Hibernate, MySQL/PostgreSQL)

RESTful APIs

Lombok

Frontend (React.js)

React with Hooks & Context API

React Router for Navigation

Axios for API Calls

Tailwind CSS / Bootstrap for UI

Other Tools & Integrations

Docker (For containerization)

Swagger (API Documentation)

JUnit & Mockito (Testing)

CI/CD (GitHub Actions / Jenkins)

Installation & Setup

Backend (Spring Boot)

Clone the repository:

git clone https://github.com/your-repo/flight-booking-system.git

Navigate to the backend directory:

cd flight-booking-system/backend

Configure application.properties with your database credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/flight_booking
spring.datasource.username=root
spring.datasource.password=yourpassword

Run the Spring Boot application:

mvn spring-boot:run

Frontend (React.js)

Navigate to the frontend directory:

cd flight-booking-system/frontend

Install dependencies:

npm install

Start the React development server:

npm start

API Endpoints

Method

Endpoint

Description

GET

/api/flights

Get available flights

POST

/api/bookings

Create a new booking

GET

/api/users/{id}

Get user details

POST

/api/auth/login

User authentication

Contribution Guidelines

Fork the repository

Create a new branch (feature-branch)

Commit changes (git commit -m 'Added new feature')

Push to GitHub (git push origin feature-branch)

Submit a Pull Request




