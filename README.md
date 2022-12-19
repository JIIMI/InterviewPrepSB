# Task at hand
- [] Fork this repo (install Git)
- [] Create a new project from https://start.spring.io/ 
  - []  Add JDBC API and H2 Database dependencies
- [] Open the project in your IDE
- [] Configure DB Access using https://spring.io/guides/gs/relational-data-access/
- [] Commit & push
- [] Move the DB code to a separate @Service
- [] Add endpoints to the project using https://spring.io/guides/gs/rest-service/
  - [] HTTP GET Endpoint will use ID param in request to retrieve Customer name from DB and print Greeting
  - [] HTTP POST Endpoint Will use ID & name param to change Customer name in DB
- [] Commit & push
- [] Add scheduling support using https://spring.io/guides/gs/scheduling-tasks/
  - [] Track all the distinct first names of Customers in cache (memory)
  - [] Check all the first names every second and compare to cache to see whether a new distinct first name appeared in DB
  - [] Add GET endpoint to list all the different first names that were/are in the DB 
- [] Commit & push
- [] Implement CRUD operations on Controller & Service
- [] Come up with some business logic to implement in Controller & Service
- [] Reimplement the Database access using https://spring.io/guides/gs/accessing-data-jpa/
  - [] Keep both JDBC and JPA access so that it can be switched on demand
- [] Implement switching of DB access method based on application property
- [] Commit & push
