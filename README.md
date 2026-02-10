🌟 Customer Feedback Management System :

Project Type: Full-Stack Web Application (Capstone)

A modern, full-stack application designed to collect, store, and analyze structured customer feedback. The project features a robust Spring Boot backend with JPA persistence and a responsive Angular frontend.

🚀 Key Features Structured Feedback: Submit ratings (1-5) and detailed comments.

Data Validation: Comprehensive backend validation using Jakarta Validation API.

Global Exception Handling: Custom error mapping for a seamless user experience.

Dynamic Dashboard: View and filter feedback based on ratings.

RESTful Architecture: Clean separation of concerns with Controller-Service-Repository layers.

🛠️ Technology Stack Frontend Framework: Angular 17+

Styling: Bootstrap 5 & Bootstrap Icons

State Management: Services & RxJS Observables

Backend Framework: Spring Boot 3.4.2

Persistence: Spring Data JPA

Database: MySQL

Validation: Hibernate Validator (Jakarta Bean Validation)

📖 How to Run Locally

Prerequisites Java 17 or higher
Node.js & NPM

Angular CLI (npm install -g @angular/cli)

Running the Backend Bash cd feedback-backend ./mvnw clean spring-boot:run 

User: sa

Running the Frontend Bash cd feedback-frontend npm install npm start UI URL: http://localhost:4200
📂 Project Structure (Evaluation Ready) Plaintext Capstone_Project_Fixed/ ├── feedback-backend/ │ ├── src/main/java/com/example/feedback_backend/ │ │ ├── controller/ # REST Endpoints │ │ ├── model/ # JPA Entities & Validation │ │ ├── service/ # Business Logic │ │ ├── repository/ # Data Access Layer │ │ └── exception/ # Global Error Handling │ └── pom.xml # Dependency Management ├── feedback-frontend/ │ ├── src/app/ │ │ ├── components/ # UI Components │ │ ├── services/ # API Integration │ │ └── models/ # TypeScript Interfaces └── README.md # Documentation 📝 Evaluation Checklist Status [x] Project Structure: Organized into Controller-Service-Repository.

[x] Validation: Handled via Jakarta Validation.

[x] REST API: Implemented with ResponseEntity and proper HTTP status codes.

[x] Global Exception Handling: Implemented via @RestControllerAdvice.

[x] Naming Conventions: Follows standard Java/Angular best practices.
