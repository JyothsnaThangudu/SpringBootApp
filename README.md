<img width="1920" height="1140" alt="Screenshot 2025-07-13 083946" src="https://github.com/user-attachments/assets/1513d95f-9492-4366-b858-4234004f1a9f" />
# Spring Boot Starter Application

This is a simple Spring Boot application built with Java 21 and Maven. It starts a local web server at `http://localhost:8080` and connects to a MySQL database named `hms_db`.

## 🚀 Features

- Displays a welcome message on the root URL (`/`)
- Configured to connect with a MySQL database
- Organized project structure using controller layer
- Uses Spring Boot Actuator for application monitoring

## 🛠️ Tech Stack

- Java 21  
- Spring Boot 3.x  
- Maven 3.9.3+  
- Spring Web  
- Spring Data JPA  
- MySQL Driver  
- MySQL Workbench


## ⚙️ Configuration

Update `application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/hms_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect



▶️ How to Run
1.Clone the repository
2.Open the project in IDE
3.Configure your MySQL credentials in application.properties
4.Run the application from SpringbootappApplication.java
5.Visit: http://localhost:8080 to see the welcome message


