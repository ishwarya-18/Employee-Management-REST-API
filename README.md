# Employee Management REST API

A Spring Boot REST API project for managing employee records with CRUD operations using MySQL database integration.

## Features

* Add Employee
* Get All Employees
* Get Employee By ID
* Update Employee
* Delete Employee

## Tech Stack

* Java
* Spring Boot
* Spring MVC
* MySQL
* JPA
* REST APIs
* Postman

## API Endpoints

| Method | Endpoint            | Description        |
| ------ | ------------------- | ------------------ |
| POST   | /api/employees      | Add Employee       |
| GET    | /api/employees      | Get All Employees  |
| GET    | /api/employees/{id} | Get Employee By ID |
| PUT    | /api/employees/{id} | Update Employee    |
| DELETE | /api/employees/{id} | Delete Employee    |

## Sample JSON

```json
{
  "name": "Ishwarya",
  "email": "ishwarya@example.com",
  "department": "Software Development",
  "salary": 30000
}
```

## How to Run

1. Create MySQL database:

```sql
CREATE DATABASE employeedb;
```

2. Configure database username and password in `application.properties`

3. Run the Spring Boot application

4. Test APIs using Postman

## Author

ISHWARYA R
