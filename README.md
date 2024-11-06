# Hospital Management System
- Developed a Spring Boot application to manage doctor and patient information with a RESTful API.
- Designed and implemented endpoints for creating, retrieving, and managing records for doctors and patients.
- Used JPA to map relational database tables, enabling efficient CRUD operations.
- Integrated exception handling for invalid data retrieval using custom exceptions.

## Technologies Used

*Backend Framework:* `` Spring Boot `` <br>
<br>
*Database:* ` MySQL ` <br>
<br>
*REST Client:* ` Postman ` <br>
<br>
*Testing:* ` JUnit 5 ` <br>
<br>
*Tools:* ` Maven ` <br>

## Dependencies
~~~
<dependencies>

  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-jpa</artifactId>
  </dependency>

  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
  </dependency>

  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
    <scope>runtime</scope>
    <optional>true</optional>
  </dependency>

  <dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <scope>runtime</scope>
  </dependency>

  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-test</artifactId>
    <scope>test</scope>
  </dependency>

<dependencies>
~~~

## API Endpoints

### Doctor Endpoints

| Method | Endpoint               | Description                    |
|--------|------------------------|--------------------------------|
| GET    | `/api/v1/doc_info`      | Retrieve all doctors           |
| GET    | `/api/v1/doc_info/{id}` | Retrieve a doctor by ID        |
| POST   | `/api/v1/doc_info`      | Add a new doctor               |

### Patient Endpoints

| Method | Endpoint                  | Description                    |
|--------|---------------------------|--------------------------------|
| GET    | `/api/v1/patients_info`    | Retrieve all patients          |
| GET    | `/api/v1/patients_info/{id}` | Retrieve a patient by ID      |
| POST   | `/api/v1/patients_info`    | Add a new patient              |
