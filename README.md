# Dance-Studio
### Project Overview 

This project is a Java-based fitness application that focuses on dancing as a form of exercise. 
It was created during the COVID-19 pandemic to help users stay physically healthy and fit. The application provides a platform for users to connect with trainers and improve their fitness through dance exercise. It also includes options for both users and admins to sign up and access different features.



<img width="1000" alt="Screenshot 2023-04-08 at 6 26 13 PM" src="https://user-images.githubusercontent.com/74003155/230722348-c0081504-87c3-4b67-bc60-aab38f81ed1a.png">




 ### Getting Started

To get started with the project, you will need to download and install the following software :computer:
*	Eclipse IDE for Java developers
*	JDBC driver for database connectivity
*	Oracle database for data storage

### User Guide
As a user, you can sign up for an account, browse through different dance exercise programs, and connect with trainers. To sign up, simply navigate to the sign-up page and provide your details. Once you have an account, you can log in and access your profile and program details. You can also search for trainers and send them messages to request training sessions.

### Admin Guide
As an admin, you have access to additional features such as managing users, programs, and trainers. You can add or remove users, create or edit dance exercise programs, and manage trainer accounts. To access the admin features, you will need to log in as an admin and navigate to the admin dashboard.

### Database Schema

The project uses an Oracle database to store user, program, and trainer data. The database schema includes tables for users, admin, trainers, and messages. Here is a sample schema:

|Table names |Table columns |
| ------------- | ------------- |
|User Table     | ID,	Name,	Email,	    Password,	   Role,	Duration|
| Admin Table   | ID,	Name,	Email,	    Description, Duration,	Difficulty|
| Trainer Table | ID,	Name,	Email,	    Description, Duration|
| Message Table | ID,	Sender,	Receiver,	Subject,	Content|

### Technologies Used
The project uses the following technologies:

|   |  |
| ------------- | ------------- |
|HTML           |CSS            |
|XML                |DTD|
|XSD                |Servlets|
|JSP                |Spring Boot|
|Spring MVC|	JDBC|
|Hibernate Framework|Hibernate Query Language|







### Code Structure
The project follows a standard Java code structure, with packages for controllers, models, services, and utilities.
- [x] The controllers handle user requests and responses. :+1:
- [x] The models define the data structures, the services provide business logic. :+1:
- [x] The utilities provide helper functions. :+1:

> scr directory contains all of the source material for building the project
1. CreateUserServlet.java
2. AdminLogin.java
3. LoginServlet.java
4. logout.java

### Testing
* The project includes unit tests using JUnit for testing the different components of the application. 
* The tests cover user authentication, program creation, trainer management, and message sending. 
* You can run the tests from Eclipse or from the command line using the Maven build tool.

### Known Issues

:-1: Message user to trainer




### Future Work

<details>

<summary>Here are some potential future improvements to the project:</summary>


```Add support for video tutorials and live training sessions```

```Integrate with popular fitness tracking apps and wearables```

```Implement more advanced machine learning algorithms for program recommendations```

```Expand the program database to include more diverse dance styles and fitness```


</details>

