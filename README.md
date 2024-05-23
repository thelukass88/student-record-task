# student-record-task
Student Record for Interview (using Java, Springboot and REST API)
![Github licence](https://img.shields.io/badge/your_licence:-MIT-blue.svg)

## Description
Assumptions:

A student record requires the following fields: student id, first name, surname, date of birth, sex, gender, phone number, address.

Tasks:

· Build a RESTful API with the following specification:

- GET /student – retrieve all students

- GET /student/{id} – retrieve student with supplied ID

- POST /student – create a new student from the supplied data.

- PUT /student/{id} – update an existing student.

- DELETE /student/{id} – delete the student with the supplied ID

· You may use either an in-memory database or any other database tool to hold your student records.

· Build a test suite for your code.

· Bonus: Build a simple UI to interact with the API
## Table of Contents
* [Installation](#installation)
* [Notes](#notes)
* [Licence](#licence)
* [Contributions](#contributors)
* [Testing](#tests)
* [Questions](#questions)
## Bugs
Key issues:
- Could not get the backend and frontend to connect. Main issue being that I cannot get the page to appear on localhost:8080 (although this may be because there is no data to display?)
- 'cannot find symbol' error persists despite following advice to include .mvn. Lack of familiarity with JAR

Next Time:
- Start by creating a simpler database and testing earlier
## Notes
- Used SpringBoot framework for setup of Java
- I believe I successfully created the student class and added the 'getters' and 'setters'
Psuedo-code:
1. Define Student Model ()
2. Setup H2 in-memory database (application.properties)
3. Create a RESTful API:
    a. Create Student repository interface
    b. Create a Service Request for Business Logic
    c. Create a REST Controller to handle HTTP requests
4. Create a TEST class for Controller
5. Create simple UI using index.html and Script JS
## Licence
Your application is licenced under: MIT
## Packages
Spring Web
Spring Data JPA
H2 Database
Lombok
Spring Boot DevTools
## Tests
N/A
## Questions
If you would like to contact me<br>
visit: [github/thelukass88](https://github.com/thelukass88)<br>
email: l.holliday88@hotmail.com