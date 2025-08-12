# Airbnb Clone Project

This project is a full-stack clone of the popular accommodation booking platform AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment.

## Frontend

### Project Goals

1. Learn to implement responsive UI/UX designs
2. Understand how to structure a complex web application
3. Practice working in a team with defined roles
4. Develop skills in component-based frontend architecture
5. Learn best practices for web application development

### Technology Stack

- <b>Frontend</b>: HTML, CSS, JavaScript (React or similar framework)
- <b>Version Control</b>: Git and GitHub
- <b>Design Tools</b>: Figma for UI/UX design

### UI/UX Design Planning

The primary design goal is to create a user-friendly, intuitive, and visually appealing interface that makes finding, booking, and managing properties easy for both guests and hosts.

The key features to be implemented are:

- <b>User-friendly Navigation</b>: A clean and logical layout that helps users effortlessly browse properties and manage their accounts.
- <b>Responsive Design</b>: The interface must adapt seamlessly to different screen sizes, from desktops to mobile devices, to ensure a consistent experience.
- <b>Visually Engaging Listings</b>: High-quality photos and clear property details will make listings attractive and informative.
- <b>Streamlined Booking Flow</b>: A simple, step-by-step process for booking a property, from selecting dates to making a payment.
- <b>Intuitive Review System</b>: An easy way for guests to leave reviews and ratings, and for hosts to respond.
- <b>Clear User Dashboard</b>: A centralized place for users to manage their bookings, listings (for hosts), and profile information.

#### Primary Pages

| Page Name             | Description                                                                                                                                                 | Key Components                                                                                                                                                                                                                                                                                                                                                                                                 |
| :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Property Listing View | This is the main search results page where users can browse properties. It showcases a grid of listings based on search criteria.                           | <b>Search Bar</b>: For location, dates, and number of guests. <b>Filters</b>: Options to narrow down results by price, amenities, property type, etc. <b>Property Cards</b>: Each card displays a high-quality image, title, price per night, and a star rating.                                                                                                                                               |
| Listing Detailed View | This page provides comprehensive information about a single property. It's designed to give the user all the information needed to make a booking decision. | <b>Image Gallery</b>: High-resolution photos of the property. <b>Detailed Description</b>: A full breakdown of the property's features, rules, and host information. <b>Booking Calendar</b>: An interactive calendar to check availability and select dates. <b>Price Breakdown</b>: A clear summary of the total cost, including fees. <b>Review Section</b>: Displays reviews and ratings from past guests. |
| Simple Checkout View  | This page is the final step in the booking process. It presents a summary of the booking and guides the user to payment.                                    | <b>Booking Summary</b>: Confirms the selected dates, property, and total price. <b>Guest Information Form</b>: Fields to enter contact and guest details. <b>Payment Integration</b>: A secure form to enter payment details (credit card, etc.). <b>Confirmation Button</b>: A clear call-to-action to finalize the booking.                                                                                  |

#### Importance of a User-Friendly Design

A user-friendly design is paramount for a booking system because it directly impacts conversion rates, user trust, and overall satisfaction. If the interface is difficult to navigate, users will likely abandon their search or booking process, leading to lost revenue. A well-designed system, however, builds trust by providing a clear and transparent experience.

#### Typography

The design uses a consistent and readable typography system:

- Font Family: Inter (or a similar sans-serif font like Roboto or Lato)

- <b>Headings (e.g., H1)</b>:

  - Font Weight: Bold (700)
  - Font Size: 32px

- <b>Subheadings (e.g., H2)</b>:

  - Font Weight: SemiBold (600)
  - Font Size: 24px
  -

- <b>Title Text</b>:

  - Font Weight: SemiBold (500)
  - Font Size: 18px

- <b>Body Text</b>:

  - Font Weight: Regular (400)
  - Font Size: 14px

- <b>Small Text/Captions:</b>

  - Font Weight: Regular (400)
  - Font Size: 12px

- <b>Buttons/Labels:</b>
  - Font Weight: SemiBold (600)
  - Font Size: 14px

#### Color Styles

- <b>Primary</b>: #34967C (A vibrant zomp used for main calls to action, buttons, and key interactive elements.)
- <b>Secondary</b>: #161117 (A neutral licorice for the footer.)
- <b>Accent</b>: #FFA800 (A green used for subtle accents and positive feedback)
- <b>Shimmer</b>: #EBEBEB
- <b>Dark</b>: #343A40
- <b>Light</b>: #F8F9FA
- <b>Black</b>: #000000
- <b>White</b>: #FFFFFF
- <b>Text (Primary)</b>: #212529 (A dark charcoal color for body text to ensure readability.)
- <b>Text (Secondary)</b>: #6C757D (A lighter gray for secondary text, labels, and captions.)

#### Importance of Identifying Design Properties

Identifying the design properties of a mockup is <b>crucial for ensuring consistency and accuracy in the development process</b>. It acts as a <b>blueprint</b> for the front-end developer, guaranteeing that the final product looks and feels exactly as the designer intended. This process prevents arbitrary choices and reduces the time spent on "pixel-perfecting" the interface.

### UI Component Patterns

#### Navbar (Navigation Bar)

The Navbar is the primary navigation component at the top of every page. It will be sticky to ensure it's always visible for easy access.

- <b>Logo</b>: The brand logo on the left.
- <b>Search Bar</b>: A prominent search bar allowing users to find properties by location and dates.
- <b>Navigation Links</b>: Links for "Become a Host," "Help," and user-related actions like "Sign Up," "Log In," or a user profile dropdown.
- <b>User Dropdown</b>: Once logged in, a dropdown menu with options like "My Profile," "My Bookings," and "Log Out."

#### Property Card

This component is used to display a summary of a property listing in a visually appealing card format. It's the key component on the "Property Listing View" page.

- <b>Image Carousel</b>: A gallery of images that users can scroll through to see different photos of the property.
- <b>Title & Location</b>: A bold title with the property name and a subtitle for the location (city, country).
- <b>Rating</b>: A star rating and the number of reviews.
- <b>Price</b>: The price per night in a clear, bold font.
- <b>Favorite Button</b>: A heart icon that allows users to save the property to a wishlist.

#### Footer

The Footer is located at the bottom of every page and contains essential links and information.

- <b>Site Map</b>: Links to key sections like "About Us," "Careers," "Press," and "Help Center."
- <b>Social Media Icons</b>: Links to the company's social media pages (e.g., Twitter, Facebook, Instagram).
- <b>Legal & Copyright</b>: Copyright information, terms of service, and privacy policy links.

#### Calendar Component

This component allows users to select check-in and check-out dates. It will be interactive, showing which dates are available.

- <b>Month View</b>: Displays a calendar for one or two months at a time.
- <b>Date Selection</b>: Users can click to select a check-in and check-out date.
- <b>Availability Display</b>: Unavailable dates will be grayed out and unclickable.

#### Button

The Button component is a fundamental, reusable element for user interactions.

- <b>Primary Button</b>: A prominent, colorful button for major calls to action (e.g., "Book Now," "Sign Up").
- <b>Secondary Button</b>: A less prominent button for secondary actions (e.g., "Cancel," "Learn More").
- <b>Outline Button:</b> A transparent button with a colored border for tertiary actions.
- <b>Disabled State:</b> A visual style for buttons that are temporarily inactive.

#### Review Card

This component displays individual reviews left by guests on the "Listing Detailed View" page.

- <b>Reviewer Information</b>: The reviewer's profile picture, name, and the date of the review.
- <b>Rating</b>: The star rating given by the reviewer.
- <b>Review Text</b>: The full text of the review.

### Project Roles and Responsibilites

#### 1. Business analyst (BA)

- Understands customer’s business processes.
- Translates customer business needs into requirements.

#### 2. Product owner (PO)

- Holds responsibility for a product vision and evolution.
- Makes sure the final product meets customer requirements.

#### 3. Project manager (PM)

- Makes sure a product or its part is delivered on time and within budget.
- Manages and motivates the software development team.

#### 4. UI/UX designer

- Transforms a product vision into user-friendly designs.
- Creates user journeys for the best user experience and highest conversion rates.

#### 5. Software architect

- Designs a high-level software architecture.
- Selects appropriate tools and platforms to implement the product vision.
- Sets up code quality standards and performs code reviews.

#### 6. Software developer

- Engineers and stabilizes the product
- Solves any technical problems emerging during the development lifecycle.

#### 7. Quality assurance (QA) engineer

- Makes sure an application performs according to requirements.
- Spots functional and non-functional defects.

#### 8. Test automation engineer

- Designs a test automation ecosystem.
- Writes and maintains test scripts for automated testing.

#### 9. DevOps engineer

- Facilitates cooperation between development and operations teams.
- Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.

## Backend

### Project Goals

1. <b>User Management</b>: Implement a secure system for user registration, authentication, and profile management.
2. <b>Property Management</b>: Develop features for property listing creation, updates, and retrieval.
3. <b>Booking System</b>: Create a booking mechanism for users to reserve properties and manage booking details.
4. <b>Payment Processing</b>: Integrate a payment system to handle transactions and record payment details.
5. <b>Review System</b>: Allow users to leave reviews and ratings for properties.
6. <b>Data Optimization</b>: Ensure efficient data retrieval and storage through database optimizations.

### Technology Stack

- <b>Django</b>: A high-level Python web framework used for building the RESTful API.
- <b>Django REST Framework</b>: Provides tools for creating and managing RESTful APIs.
- <b>PostgreSQL</b>: A powerful relational database used for data storage.
- <b>GraphQL</b>: Allows for flexible and efficient querying of data.
- <b>Celery</b>: For handling asynchronous tasks such as sending notifications or processing payments.
- <b>Redis</b>: Used for caching and session management.
- <b>Docker</b>: Containerization tool for consistent development and deployment environments.
- <b>CI/CD Pipelines</b>: Automated pipelines for testing and deploying code changes.

### Database Design

1. <b>Users</b>: This table stores user information, including hosts and guests.
2. <b>Properties</b>: This table holds details about each property listing.
3. <b>Bookings</b>: This table tracks all property bookings made by users.
4. <b>Payments</b>: This table records all payment transactions related to bookings.
5. <b>Reviews</b>: This table stores user reviews and ratings for properties.
6. <b>Property Amenities</b>: This table links properties to their available amenities such as WiFi, parking etc.
7. <b>Amenities</b>: This table is a lookup table for all possible amenities.
8. <b>Property Images</b>: This table stores URLs to images of the properties.

### Feature Breakdown

#### 1. API Documentation

- <b>OpenAPI Standard</b>: The backend APIs are documented using the OpenAPI standard to ensure clarity and ease of integration.
- <b>Django REST Framework</b>: Provides a comprehensive RESTful API for handling CRUD operations on user and property data.
- <b>GraphQL</b>: Offers a flexible and efficient query mechanism for interacting with the backend.

#### 2. User Authentication

- <b>Endpoints</b>: `/users/`, `/users/{user_id}/`
- <b>Features</b>: Register new users, authenticate, and manage user profiles.

#### 3. Property Management

- <b>Endpoints</b>: `/properties/`, `/properties/{property_id}/`
- <b>Features</b>: Create, update, retrieve, and delete property listings.

#### 4. Booking System

- <b>Endpoints</b>: `/bookings/`, `/bookings/{booking_id}/`
- <b>Features</b>: Make, update, and manage bookings, including check-in and check-out details.

#### 5. Payment Processing

- <b>Endpoints</b>: `/payments/`
- <b>Features</b>: Handle payment transactions related to bookings.

#### 6. Review System

- <b>Endpoints</b>: `/reviews/`, `/reviews/{review_id}/`
- <b>Features</b>: Post and manage reviews for properties.

#### 7. Database Optimizations

- <b>Indexing</b>: Implement indexes for fast retrieval of frequently accessed data.
- <b>Caching</b>: Use caching strategies to reduce database load and improve performance.

### API Security

1. <b>Authentication</b>: Verification of the identity of users in the system.
2. <b>Authorisation</b>: Determining what a verified user is allowed to do in the system.
3. <b>Rate limiting</b>: Controls the number of requests a client can make to the system API within a specific timeframe.

### CI/CD Pipeline

A <b>CI/CD pipeline</b> (Continuous Integration / Continuous Deployment) is an automated workflow that takes code from development through testing and into production with minimal manual intervention.

For this project, CI/CD is important because it:

- <b>Ensures code quality</b> — automatically runs tests and linting on every commit to catch bugs early.
- <b>Speeds up delivery</b> — new features and fixes get deployed quickly without lengthy manual steps.
- <b>Reduces errors in deployment</b> — automation ensures consistent build and deployment processes.
- <b>Supports collaboration</b> — multiple developers can contribute without breaking the app.

Possible tools for an Airbnb clone project:

- <b>Version Control & Automation</b>: GitHub Actions, GitLab CI, or Jenkins (to run builds, tests, and deploy scripts).
- <b>Containerization</b>: Docker (to package app dependencies consistently).
- <b>Orchestration / Deployment</b>: Kubernetes, Docker Compose, or AWS ECS/Fargate.
- <b>Hosting</b>: AWS, Azure, Google Cloud, or Vercel/Netlify (for the frontend).

### Team Roles

#### 1. Business analyst (BA)

- Understands customer’s business processes.
- Translates customer business needs into requirements.

#### 2. Product owner (PO)

- Holds responsibility for a product vision and evolution.
- Makes sure the final product meets customer requirements.

#### 3. Project manager (PM)

- Makes sure a product or its part is delivered on time and within budget.
- Manages and motivates the software development team.

#### 4. Software architect

- Designs a high-level software architecture.
- Selects appropriate tools and platforms to implement the product vision.
- Sets up code quality standards and performs code reviews.

#### 5. Software developer

- Engineers and stabilizes the product
- Solves any technical problems emerging during the development lifecycle.

#### 6. Quality assurance (QA) engineer

- Makes sure an application performs according to requirements.
- Spots functional and non-functional defects.

#### 7. Test automation engineer

- Designs a test automation ecosystem.
- Writes and maintains test scripts for automated testing.

#### 8. DevOps engineer

- Facilitates cooperation between development and operations teams.
- Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.
