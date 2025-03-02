# cs465
# Full Stack Web Application - README

## Overview
This repository contains the final iteration of my full stack web application, developed as part of my coursework. The project includes both customer-facing and administrative functionalities, with added security features for secure admin login authentication. This README outlines the architecture, functionality, testing, and reflections on the development process.

## Architecture
This full stack project incorporates various frontend development approaches, including:
- **Express HTML & JavaScript**: Used for server-side rendering, dynamically generating pages based on user interactions.
- **Single Page Application (SPA)**: Utilized for a seamless user experience, reducing the need for full-page reloads and enhancing performance through dynamic content updates.

### Why NoSQL (MongoDB)?
The backend leverages a NoSQL MongoDB database due to its:
- **Flexibility**: Schema-less structure allows for dynamic data storage.
- **Scalability**: Supports horizontal scaling for large datasets.
- **Ease of Integration**: Works efficiently with JavaScript and JSON-based APIs.

## Functionality
### JSON vs. JavaScript & API Integration
JSON (JavaScript Object Notation) is a lightweight data format used for exchanging data between the frontend and backend. Unlike JavaScript, which is a programming language, JSON is purely a data representation format. JSON enables seamless communication between the client and server, allowing structured data to be passed via API requests.

### Code Refactoring & UI Component Reusability
Throughout the development process, I refactored code to enhance functionality and efficiency. Notable improvements include:
- Modularizing API request handlers to improve maintainability.
- Creating reusable UI components, such as buttons and form elements, to ensure consistency and reduce redundant code.
- Optimizing database queries for faster performance.

## Testing
### API Testing & Security Considerations
Testing was conducted at multiple levels, ensuring data integrity and secure access control. Key testing methods include:
- **Unit Testing**: Validating individual functions for expected behavior.
- **Integration Testing**: Ensuring seamless interaction between frontend, backend, and database.
- **Security Testing**: Implementing authentication and authorization checks to prevent unauthorized access to admin functionalities.

Understanding methods, endpoints, and security within the full stack application was critical. API endpoints were tested for:
- Proper request handling (GET, POST, PUT, DELETE)
- Data validation and error handling
- Secure authentication with hashed passwords and session tokens

## Reflection
This course has significantly contributed to my professional growth by enhancing my skills in full stack development. I have gained proficiency in:
- **Frontend & Backend Integration**: Strengthening my ability to build seamless user experiences.
- **Database Management**: Utilizing MongoDB for efficient data storage and retrieval.
- **Security Best Practices**: Implementing authentication and authorization techniques to protect sensitive data.

These skills will help me become a more marketable candidate in the field of software development and align with my long-term career goal of becoming a data scientist.


Thank you for reviewing my project. I appreciate the opportunity to reflect on my learning journey and showcase my progress.

