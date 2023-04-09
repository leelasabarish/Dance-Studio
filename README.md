# Dance-Studio

## Project Overview 

   This project is a Java-based fitness application that focuses on dancing as a form of exercise. 
   It was created during the COVID-19 pandemic to help users stay physically healthy and fit. 
   The application provides a platform for users to connect with trainers and improve their fitness through dance exercise. 
   It also includes options for both users and admins to sign up and access different features.







## Getting Started

##### Here is a simple flow chart

<img width="1000" alt="Screenshot 2023-04-08 at 6 26 13 PM" src="https://user-images.githubusercontent.com/74003155/230722348-c0081504-87c3-4b67-bc60-aab38f81ed1a.png">

### Pre-Requirements
The system should have a 2-core processor with a speed of 2 GHz or higher, a minimum of 4 GB RAM, and at least 10 GB of free hard drive space. Java JDK should be downloaded and installed.

To started with the project, you will need to download and install the following software :computer:
*	Eclipse IDE for Java developers
*	JDBC driver for database connectivity
*	Oracle database for data storage

## Guide

### User Guide
- [x] As a user, you can sign up for an account, browse through different dance exercise programs, and connect with trainers. 
- [x] To sign up, simply navigate to the sign-up page and provide your details.
- [x] Once you have an account, you can log in and access your profile and program details. 
- [x] You can also search for trainers and send a request training sessions.

### Admin Guide
- [x] As an admin, you have access to additional features such as managing users, programs, and trainers. 
- [x] You can add or remove users, create or edit dance exercise programs, and manage trainer accounts. 
- [x] To access the admin features, you will need to log in as an admin and navigate to the admin dashboard.

### Trainer Guide
- [x] As an trainer, you have access users, programs.
- [x] You can add or remove user and add dance exercise programs.
- [x] To access the trainer features, you will need to log in as an trainer and navigate to the trainer dashboard.

## Database Schema

The project uses an Oracle database to store user, program, and trainer data. The database schema includes tables for users, admin, trainers, and messages. Here is a sample schema:

|Table names |Table columns |
| ------------- | ------------- |
|User Table     | ID,	Name,	Email,	    Password,	   Role,	Duration|
| Admin Table   | ID,	Name,	Email,	    Description, Duration,	Difficulty|
| Trainer Table | ID,	Name,	Email,	    Description, Duration|
| Message Table | ID,	Sender,	Receiver,	Subject,	Content|

## Technologies Used
The project uses the following technologies

 HTML, CSS, and JavaScript for web development.
 XML, DTD, and XSD for data validation.
 Servlets and JSP for frontend connectivity to the backend.
 Spring Boot and Spring MVC for the backend.
 JDBC and Hibernate Framework for database connectivity.
 Hibernate Query Language for querying the database.
 Apache Tomcat as the web server.
 Oracle for database management.







## Code Structure
The project follows a standard Java code structure, with packages for controllers, models, services, and utilities.
- The controllers handle user requests and responses. :+1:
- The models define the data structures, the services provide business logic. :+1:
- The utilities provide helper functions. :+1:

> scr directory contains all of the source material for building the project
1. CreateUserServlet.java
2. AdminLogin.java
3. LoginServlet.java
4. logout.java

## Testing
* The project includes unit tests using JUnit for testing the different components of the application. 
* The tests cover user authentication, program creation, trainer management, and message sending. 
* You can run the tests from Eclipse or from the command line using the Maven build tool.

## Known Issues

  `live communication` between user and trainer.




## Future Work

<details>

<summary>Here are some potential future improvements to the project:</summary>


```Add support for video tutorials and live training sessions```

```Integrate with popular fitness tracking apps and wearables```

```Implement more advanced machine learning algorithms for program recommendations```

```Expand the program database to include more diverse dance styles and fitness```


</details>

