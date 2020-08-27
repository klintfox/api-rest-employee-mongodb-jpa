# WS Rest SpringBoot y MongoDb

Servicio de ejemplo utilizando las siguietes tecnologias

- Spring Boot
- JPA
- MongoDB
- Maven
- Docker-Compose

### Métodos

- GET
  - localhost/api/v1/employees
  - localhost/api/v1/employees/id
- POST
  - localhost/api/v1/employees
  - Body  
     {
    "firstName":"klint Fitzgerald",
    "lastName":"roman",
    "emailId":"klint_f@hotmail.com"
    }
- UPDATE
  - -localhost/api/v1/employees/id
  - Body
    {
    "firstName":"klint Fitzgerald",
    "lastName":"roman",
    "emailId":"klint_f@hotmail.com"
    }
- DELETE
  - -localhost/api/v1/employees/id
