# Geolocation-Notification-Microservice
The Geolocation Notification microservice is a Spring Boot application designed to manage geolocation-based notifications. It allows users to create, retrieve, and manage notifications that are triggered based on geographical locations. This service is built using Spring Boot and MongoDB, leveraging the power of RESTful APIs for communication.

Features
Create Notifications: Users can create new geolocation notifications with specific details.
Retrieve Notifications: Users can fetch a single notification by its ID or retrieve all notifications.
Exception Handling: The service includes a global exception handler to manage errors gracefully.
Lombok Integration: Utilizes Lombok to reduce boilerplate code for model classes.
Technologies Used
Java 21: The application is built using the latest version of Java.
Spring Boot 3.4.2: The framework used for building the microservice.
Spring Data MongoDB: For data persistence and interaction with MongoDB.
Lombok: To simplify the code by reducing boilerplate.
Maven: For project management and dependency management.
Project Structure
The project is organized into several packages:

controllers: Contains the REST controllers for handling HTTP requests.
entities: Contains the data model classes.
exception: Contains custom exception classes and global exception handlers.
impl: Contains the implementation of service interfaces.
repository: Contains the MongoDB repository interfaces.
service: Contains service interfaces for business logic.
