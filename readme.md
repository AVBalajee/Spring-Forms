# Spring Boot Registration and Login Application

This is a simple Spring Boot application that demonstrates user registration and login functionality.

## Technologies Used

- Java
- Spring Boot
- Thymeleaf
- MySQL

## Setup and Configuration

1. Ensure that you have Java and MySQL installed on your system.

2. Clone the repository to your local machine.

3. Create a MySQL database using the following command:
   ```sql
   CREATE DATABASE mydatabase;


4. Open the project in your preferred IDE.
   Update the database configuration in the
   src/main/resources/application.properties file:
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/mydatabase
   spring.datasource.username=db_username  
   spring.datasource.password=db_password
   # Replace mydatabase, db_username, and db_password with your actual database name, username, and password.

5. Build the project using Maven or Gradle:
   - For Maven: mvn clean install
   - For Gradle: gradle clean build

## Running The Application:

1. Once the build is successful, run the application using the following command:
   - For Maven: mvn spring-boot:run
   - For Gradle: gradle bootRun
2. The Spring Boot application will start and run on the default port 8080.
3. Open a web browser and visit http://localhost:8080 to access the application.

## Usage:
1. Registration: Visit http://localhost:8080/register to access the registration page. Fill in the registration form and submit. Upon successful registration, you will be redirected to the login page.

2. Login: Visit http://localhost:8080/login to access the login page. Enter your credentials and submit. If the credentials are valid, you will be redirected to the dashboard page. Otherwise, an "Invalid credentials" message will be displayed.

3. Dashboard: Visit http://localhost:8080/dashboard to access the dashboard page. This page displays a welcome message with your username.

4. Logout: Visit http://localhost:8080/logout to logout from the application.
