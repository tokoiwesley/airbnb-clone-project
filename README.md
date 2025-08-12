# Airbnb Clone Project

This project is a full-stack clone of the popular accommodation booking platform AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment.

## Project Goals

### Frontend

1. Learn to implement responsive UI/UX designs
2. Understand how to structure a complex web application
3. Practice working in a team with defined roles
4. Develop skills in component-based frontend architecture
5. Learn best practices for web application development

### Backend

1. <b>User Management</b>: Implement a secure system for user registration, authentication, and profile management.
2. <b>Property Management</b>: Develop features for property listing creation, updates, and retrieval.
3. <b>Booking System</b>: Create a booking mechanism for users to reserve properties and manage booking details.
4. <b>Payment Processing</b>: Integrate a payment system to handle transactions and record payment details.
5. <b>Review System</b>: Allow users to leave reviews and ratings for properties.
6. <b>Data Optimization</b>: Ensure efficient data retrieval and storage through database optimizations.

## Technology Stack

### Frontend

- <b>Frontend</b>: HTML, CSS, JavaScript (React or similar framework)
- <b>Version Control</b>: Git and GitHub
- <b>Design Tools</b>: Figma for UI/UX design

### Backend

- <b>Django</b>: A high-level Python web framework used for building the RESTful API.
- <b>Django REST Framework</b>: Provides tools for creating and managing RESTful APIs.
- <b>PostgreSQL</b>: A powerful relational database used for data storage.
- <b>GraphQL</b>: Allows for flexible and efficient querying of data.
- <b>Celery</b>: For handling asynchronous tasks such as sending notifications or processing payments.
- <b>Redis</b>: Used for caching and session management.
- <b>Docker</b>: Containerization tool for consistent development and deployment environments.
- <b>CI/CD Pipelines</b>: Automated pipelines for testing and deploying code changes.

## Team Roles

### 1. Business analyst (BA)

- Understands customer’s business processes.
- Translates customer business needs into requirements.

### 2. Product owner (PO)

- Holds responsibility for a product vision and evolution.
- Makes sure the final product meets customer requirements.

### 3. Project manager (PM)

- Makes sure a product or its part is delivered on time and within budget.
- Manages and motivates the software development team.

### 4. UI/UX designer

- Transforms a product vision into user-friendly designs.
- Creates user journeys for the best user experience and highest conversion rates.

### 5. Software architect

- Designs a high-level software architecture.
- Selects appropriate tools and platforms to implement the product vision.
- Sets up code quality standards and performs code reviews.

### 6. Software developer

- Engineers and stabilizes the product
- Solves any technical problems emerging during the development lifecycle.

### 7. Quality assurance (QA) engineer

- Makes sure an application performs according to requirements.
- Spots functional and non-functional defects.

### 8. Test automation engineer

- Designs a test automation ecosystem.
- Writes and maintains test scripts for automated testing.

### 9. DevOps engineer

- Facilitates cooperation between development and operations teams.
- Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.

## Database Design

### Users

This table stores user information, including hosts and guests.

### Properties

This table holds details about each property listing.

### Bookings

This table tracks all property bookings made by users.

### Payments

This table records all payment transactions related to bookings.

### Reviews

This table stores user reviews and ratings for properties.

### Property Amenities

This table links properties to their available amenities such as WiFi, parking etc.

### Amenities

This table is a lookup table for all possible amenities.

### Property Images

This table stores URLs to images of the properties.

## Feature Breakdown

### 1. API Documentation

- <b>OpenAPI Standard</b>: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of integration.
- <b>Django REST Framework</b>: Provides a comprehensive RESTful API for handling CRUD operations on user and property data.
- <b>GraphQL</b>: Offers a flexible and efficient query mechanism for interacting with the backend.

### 2. User Authentication

- <b>Endpoints</b>: `/users/`, `/users/{user_id}/`
- <b>Features</b>: Register new users, authenticate, and manage user profiles.

### 3. Property Management

- <b>Endpoints</b>: `/properties/`, `/properties/{property_id}/`
- <b>Features</b>: Create, update, retrieve, and delete property listings.

### 4. Booking System

- <b>Endpoints</b>: `/bookings/`, `/bookings/{booking_id}/`
- <b>Features</b>: Make, update, and manage bookings, including check-in and check-out details.

### 5. Payment Processing

- <b>Endpoints</b>: `/payments/`
- <b>Features</b>: Handle payment transactions related to bookings.

### 6. Review System

- <b>Endpoints</b>: `/reviews/`, `/reviews/{review_id}/`
- <b>Features</b>: Post and manage reviews for properties.

### 7. Database Optimizations

- <b>Indexing</b>: Implement indexes for fast retrieval of frequently accessed data.
- <b>Caching</b>: Use caching strategies to reduce database load and improve performance.

## API Security

1. <b>Authentication</b>: Verification of the identity of users in the system.
2. <b>Authorisation</b>: Determining what a verified user is allowed to do in the system.
3. <b>Rate limiting</b>: Controls the number of requests a client can make to the system API within a specific timeframe.

## CI/CD Pipeline
