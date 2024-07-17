# Job Application Management System

This Java project is a simple CRUD (Create, Read, Update, Delete) application designed to manage job listings. It provides basic functionalities to add, update, delete, and search for job entries.

## Technologies Used

- **Java**: Core programming language used for backend development.
- **Spring Boot**: Framework for creating standalone, production-grade Spring-based applications.
- **Spring Data JPA**: Simplifies the implementation of data access layers.
- **PostgresQL**: Relational database management system used to persist job data.

## Getting Started

To run this project locally, ensure you have Java and PostgresQL installed. Clone the repository, configure your MySQL database settings in `application.properties`, and run the application.

```bash
git clone https://github.com/anngpham/JobApp.git
cd JobApp
# Set up your PostgresQL database settings in src/main/resources/application.properties
mvn spring-boot:run
