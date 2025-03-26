# Spring-Task-Manager
Task Management System
A Spring Boot and SQL-based web application for managing tasks and projects, with an automated deadline scheduler to check for expired deadlines.

📌 Features

✔ Task & Project Management – Create, update, and track tasks.

✔ User Authentication – Secure login and role-based access.

✔ Deadline Scheduler – Automated background job checks for expired deadlines and sends alerts.

✔ RESTful API – Full CRUD operations for tasks and projects.

✔ Database Integration – Uses SQL (MySQL/PostgreSQL/H2) for data persistence.


🛠 Technologies Used

Backend: Spring Boot (Java)

Database: SQL (MySQL/PostgreSQL/H2)

Scheduling: Spring Scheduler (@Scheduled)

API Documentation: Swagger/OpenAPI (optional)

Frontend: Thymeleaf/React (if applicable)

🚀 Getting Started

Prerequisites

Java 17+

Maven

MySQL/PostgreSQL (or H2 for development)

Setup & Run

Clone the repository:

git clone https://github.com/TallOrder/Spring-Task-Manager.git
cd task-management-system


Configure the database:


Update application.properties (or application.yml):

spring.datasource.url=jdbc:mysql://localhost:3306/taskdb
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

Run the application: on cmd enter mvn spring-boot:run

The app will start at: http://localhost:8080

Access APIs:

REST Endpoints:

GET /api/tasks – List all tasks

POST /api/tasks – Create a new task

PUT /api/tasks/{id} – Update a task

DELETE /api/tasks/{id} – Delete a task
