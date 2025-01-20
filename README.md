# Student API Project

This repository contains the source code for a Student Management API. The project is designed to facilitate the management of student records, including adding, updating, retrieving, and deleting information.

## Features
- **Student Records:** Add, update, view, and delete student data.
- **Course Management:** Manage the courses assigned to students.
- **Authentication and Authorization:** Role-based access control for secure API usage.

## Technologies Used
### Backend
- **Language:** Java
- **Framework:** Spring Boot
- **Database:** MySQL
- **Other Tools:** Hibernate, JPA, Spring Security

## Prerequisites
To run this project, ensure you have the following installed:
- Java 15 or later
- MySQL Server

## Installation and Setup

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/GinaRM/studentAPI.git
   cd studentAPI/backend
   ```
2. Configure the database:
   - Create a MySQL database named `student_management`.
   - Update the database connection properties in `application.properties`.

3. Build and run the backend:
   ```bash
   ./mvnw spring-boot:run
   ```

The application should now be accessible at `http://localhost:8080`.

## Usage
1. Use an API client such as Postman or curl to interact with the endpoints.
2. Perform CRUD operations on student records and manage course assignments.

## Testing
- Run backend tests:
  ```bash
  ./mvnw test
  ```

## Contributing
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git commit -m "Description of changes"
   git push origin feature-name
   ```
4. Open a pull request.



## Contact
For questions or suggestions, please contact [Gina Rodríguez](https://github.com/GinaRM).
