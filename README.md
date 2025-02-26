# EduManage - Student and Course Management System

## Project Title
EduManage - Student and Course Management System

## Project Context
EduManage aims to develop an internal web application for managing students and courses. This application will allow administrators to view, add, modify, and delete students and courses through a user-friendly and intuitive interface.

The project will follow the MVC architecture to ensure a clear separation of responsibilities between data management, business logic, and user interface. A relationship between students and courses will be established, allowing multiple students to be associated with multiple courses.

## Technologies Used
- **Backend**: Java EE (Servlets, JSP, JDBC), Maven
- **Database**: MySQL
- **Frontend**: HTML, CSS, Bootstrap, JavaScript
- **Application Server**: Apache Tomcat
- **Development Tools**: Eclipse or IntelliJ

## Design (UML Diagrams)
To better structure the architecture of the application, two UML diagrams will be created:

1. **Class Diagram**: This diagram represents the main classes of the project and their relationships.
2. **Use Case Diagram**: This diagram illustrates the interactions between actors and the various functionalities of the system.

## Implementation of CRUD Features

### Student Management
- **Create**: Add a new student via a form including Name, First Name, Email, and Date of Birth.
- **Read**: Display a list of students with filtering and search capabilities.
- **Update**: Modify a student's information via a pre-filled form.
- **Delete**: Remove a student after confirmation.

### Course Management
- **Read**: Display a list of existing courses.
- **Create**: Add a new course with Course Name and Description.
- **Update**: Modify a course's information via a form.
- **Delete**: Remove a course after confirmation.
