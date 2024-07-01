# Spring Security JWT Authentication and Authorization

If you find this repository useful, please help us by starring it! 😊

## Technologies Used

- JDK 17
- Spring Boot 3
- Spring Data JPA
- Spring Security 6
- PostgreSQL 15
- Java JWT
- Docker

## Prerequisites

Make sure you have the following components installed in your development environment before you start:

1. [Git](https://git-scm.com/downloads)
2. [Docker](https://docs.docker.com/compose/install/)

## Environment Setup

#### Clone the repository to your local machine



```
[git clone https://github.com/Angel-Raa/spring-security-jwt-authentication-and-authorization.git](https://github.com/SarbajitNeogi/Springboot-JWT.git)
```
#### Navigate to the project directory

Go to the newly cloned project directory using the following command:
```
cd spring-security-jwt-authentication-and-authorization
```

#### Create and Configure `file.env` and `db.env`

You need to create two configuration files, `file.env` and `db.env`, in the root directory of the cloned repository.

**file.env**
This file contains the environment variables for the application.
```bash
SPRING_DATASOURCE_URL=jdbc:postgresql://database:5432/your_database
SPRING_DATASOURCE_USERNAME=your_username
SPRING_DATASOURCE_PASSWORD=your_password
SPRING_JPA_PROPERTIES_HIBERNATE_DIALECT=org.hibernate.dialect.PostgreSQLDialect
SPRING_JPA_HIBERNATE_DDL_AUTO=update
SPRING_JPA_SHOW=true

```
**db.env** 
This file contains the credentials for the database.
```bash
POSTGRES_DB=your_database_name
POSTGRES_PASSWORD=your_database_password
POSTGRES_USER=your_database_user
```
Make sure to replace your_database, your_username, your_password, your_database_name, your_database_password, and your_database_user with the appropriate values for your setup.

#### Build and run the Docker Compose containers
```
docker compose up -d
```

### Swagger Documentation
```
http://localhost:8000/api/v1/swagger-ui/index.html#/
```
![](https://github.com/Angel-Raa/spring-security-jwt-authentication-and-authorization/blob/main/src/main/resources/img/docs.png)


## Additional Resources

Here are some additional resources that might be useful:
- [Documentacion de Spring Data](https://spring.io/projects/spring-data)
- [Documentación de Java JWT](https://github.com/jwtk/jjwt)
- [Documentacion de open jdk 17](https://docs.oracle.com/en/java/javase/17/docs/api/)
- [Documentacion de Spring boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Documentacion de Maven](https://maven.apache.org/guides/getting-started/)
- [Documentacion de Docker](https://docs.docker.com/)
- [Documentacion de Spring Security](https://docs.spring.io/spring-security/reference/index.html)
- [Documentacion de Git](https://git-scm.com/doc)




