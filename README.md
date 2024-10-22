# Book Store Management System

A Spring Boot application for managing book inventories, listings, and user interactions in a bookstore.

## Features
- Add, update, and delete books
- List and search available books
- Manage book categories
- User-friendly interface

## Tech Stack
- **Backend:** Spring Boot, Spring Data JPA
- **Frontend:** Thymeleaf, Bootstrap/Tailwind CSS
- **Database:** MySQL (JPA + Hibernate)
- **Tools:** Maven, VS Code

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/book-store-spring.git
   ```
2. Navigate to the project directory:
  ```bash
  cd book-store-spring
  ```
3. Configure MySQL database in application.properties:
  ```bash
  spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
  spring.datasource.username=root
  spring.datasource.password=yourpassword
  ```
4. Run the application:
  ```bash
  mvn spring-boot:run
  ```
## Usage

Access the application at http://localhost:8080 and start managing your bookstore inventory!

