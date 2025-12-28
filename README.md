# Employee Management System (Spring MVC)

## Project Title
Employee Management System (MVC Based Web Application)

## Project Description
The Employee Management System is a web-based application developed using Spring MVC, JSP, and MySQL.  
The application follows the MVC (Model-View-Controller) architecture and provides complete CRUD operations for managing employee records.

## Architecture (MVC Pattern)

### Model
- Employee Entity
- DAO Layer (EmployeeDAO, EmployeeDAOImpl)
- Service Layer (EmployeeService, EmployeeServiceImpl)

### View
- JSP Pages using HTML and CSS
- addEmployee.jsp
- editEmployee.jsp
- listEmployee.jsp

### Controller
- Spring MVC Controller (EmployeeController)

## Technologies Used
- Java (JDK 17+)
- Spring MVC
- JSP & JSTL
- JDBC
- MySQL Database
- Apache Tomcat 10
- Maven
- Eclipse IDE

## Employee Fields
- Employee ID
- Name
- Email
- Department
- Salary
- Date of Joining

## Application Features
- Add new employee
- View all employees
- Update employee details
- Delete employee record
- Proper navigation between pages
- MVC architecture followed strictly

## Database Details

### Database Name
ems_db

### Table Creation Script
```sql
CREATE DATABASE ems_db;
USE ems_db;

CREATE TABLE employee (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    department VARCHAR(50),
    salary DOUBLE,
    date_of_joining DATE
);

## Screenshots

### Add Employee Page
![Add Employee](screenshots/add_employee.png)

### Employee List Page
![Employee List](screenshots/employee_list.png)

### Edit Employee Page
![Edit Employee](screenshots/edit_employee.png)








