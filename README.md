# Task Management System

The Task Management System is a simple web application that allows users to manage their tasks efficiently. It provides basic functionality for creating, updating, and deleting tasks, as well as user authentication to ensure a personalized experience.

## Features

- **User Authentication:**
  - Register a new account.
  - Log in with existing credentials.
  - Log out securely.

- **Task Management:**
  - Create tasks with details like title, description, due date, and status.
  - View a list of tasks associated with the logged-in user.
  - Update task details.
  - Delete tasks.

- **User Profile (Optional):**
  - View and edit user profile information.

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf (or your preferred template engine)
- H2 Database (for simplicity, you can replace it with another database in production)
- (Add any other technologies/frameworks you used)

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/joshravichandar/task-management-system.git
   cd task-management-system
2. **Run this project:**
   ```bash
   ./mvnw spring-boot:run
3. **Explore and test:**
   - Open your web browser and navigate to http://localhost:8080.
   - Register a new account, log in, and start managing your tasks.
  
## Project Structure
- src/main/java: Java source files.
- src/main/resources: Application configuration and static resources.
- src/main/resources/templates: Thymeleaf templates.
- src/test: Test files.

## Additional Notes
- This project uses an H2 in-memory database for simplicity. In a production environment, consider using a more robust database like MySQL or PostgreSQL.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
