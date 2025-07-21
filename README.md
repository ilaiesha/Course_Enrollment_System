# 📚 Course Enrollment System

This is a "Spring Boot" project that allows students to enroll in courses offered by instructors. 
It follows a RESTful API design and uses MySQL as the database.
The project is built using Spring Tool Suite (STS) and tested using Postman.


# 🔧 Technologies Used

- Java
- Spring Boot (STS)
- MySQL
- JPA/Hibernate
- REST APIs
- Postman (for testing)
- Maven


# 📁 Project Structure

   ->  Entity Layer – Contains classes for Student, Instructor, Course, and Enrollment.
   ->  Repository Layer – Interfaces that extend `JpaRepository` for CRUD operations.
   ->  Service Layer – Contains business logic for the application.
   ->  Controller Layer – Exposes REST APIs for frontend or Postman.
   ->  Exception Layer – Handles custom exceptions and global error responses.
   ->  Helper & ResponseStructure – Used for response formatting and additional logic.


# 📌 Features

   - Add, update, delete students, instructors, and courses.
   - Enroll a student into a course.
   - View enrollment details.
   - Proper validation and exception handling.
   - Clean and modular project structure.



# 🗄️ Database Configuration

In application.properties, set your MySQL database details:

properties are:-
spring.datasource.url=jdbc:mysql://localhost:3306/course_enrollment
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


# 📮 Testing with Postman
Use Postman to test various APIs like:

POST /student – Add new student
POST /instructor – Add instructor
POST /course – Add course
POST /enroll – Enroll student in course
GET /student/{id} – Get student by ID
GET /course/{id} – Get course by ID
DELETE /student/{id} – Delete student

# 🙋‍♀️ Author
   ILA IESHA
