
# Task Description

This task was assigned during the `Notch Devcademy` course. It involved students who had passed the first elimination circle, gathering in Hackathon, Zagreb, at their office. The given chellange was to present the implementation of a Staycation API.

## Context:
The task was part of a practical exercise within the curriculum of Devcademy. Students, having advanced through the initial selection process, were brought together for a hands-on session where they had to apply their skills to create and integrate a Staycation API.

## Technology Stack:
- **Programming Language:** Java
- **Framework:** Spring Boot
  
# Disclaimer
- Data presented in the database diagram and available on the day 2 of Event   
- Application should implement N-tier architecture:
    - Controller
    - Dto
    - Service
    - Repository  
- In request/response are described DTO objects, it is mandatory to follow those naming conventions in data model.
- Test data are available on day 2 of Event.
- Only complete endpoints will be considered in grading.

# Assumptions
- There is no real security layer (for now), but in every request expect `/login` user should send `Authentication Bearer {token}` header.
- All request fields are required unless indicated.
- If a required request field is missing the HTTP Response Code 400 (Bad Request) should be returned.
- The standard HTTP Response Code is 200; unless indicated otherwise.
- The error HTTP Response Code is 500; unless indicated otherwise.

# Requirements
- The requirements for the application are specified using given user stories.
- Higher number of correctly implemented stories means more points.

## Architecture Overview
The architecture for the Staycation API involves a user role accessing the web application, which in turn communicates with the implemented API. The API, developed using Spring Boot and Java, interacts with a MySQL database to store and retrieve data.  

![Architecture Diagram](./docs/img/staycation-app-architecture.png)
*Architecture Diagram: A representation of the interaction between the user role, web application, API, and MySQL database.*

For detailed user stories and required DTO models for request handling and returning response, refer to the [PDF document](./docs/staycation-api.pdf).