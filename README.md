# Spring Boot Blog Application

This is application for Java Spring Boot using:

- H2 Database
- Thymeleaf
- Model View Controller (MVC) architecture
- Spring Data JPA
- Spring Security



## Development Instructions

Run this command:

- `mvnw spring-boot:run`
  
- open http://localhost:8080

## Built-in Account and Constraints

- Login as a User with `user.user@domain.com` and password `password`
- Login as an Admin with `admin.admin@domain.com` and password `password`
- An **Anonymous** account can only `READ` Posts
- A **User** account can `CREATE, READ, UPDATE` Posts
- An **Admin** account can `CREATE, READ, UPDATE, DELETE` Posts

Description:

The University Blogging Website is a platform designed to facilitate knowledge sharing, collaboration, and community building within your university. It provides students, faculty, and staff members with a dedicated space to publish and explore blog posts related to various subjects and interests. Leveraging the Java ecosystem, including Spring and jdbc. Let's explore the key features and components of the project.
