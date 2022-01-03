SYNERGY Hotel APP for booking, viewing and handeling reservations (For clients and employees)

Description
Synergy Hotel Mangament System is an application for both users and employees to interact with our organization. Users can login, make reservations, view/update existing reservations, and manage their accounts. Employees can view and manage reservations. Our application includes a fully integrated calendar API (FullCalendar) for vacation planning as well as an API to check the weather at our many locations.

Technologies used:

RDBMS for persistence
API built with Java 8 and Spring 5
Java API uses Hibernate to communicate with a PostGreSQL RDBMS
Java API leverages the Spring Framework
Java API is RESTful (JWTs)
Complete CI/CD pipelines uses AWS (CodePipeline, CodeBuild, Elastic Beanstalk, and S3)

Features

(Clients)
Sign up for an account
Log in and out
Change information: first name, last name, email, and password
Make reservations for specific dates
Make specific accommodation requests
Update reservation dates

(Employees)
Log in and out
Change information: first name, last name, and password
Approve or Deny reservations
Change room availability
View the status of all rooms

(Managers)
All abilities that an Employee has
Add employee and other manager accounts
Change room prices by changing amenity prices
Add rooms to the system

Application  leverages at two external APIs
RDBMS is deployed to the cloud (AWS RDS)
Java API is deployed to the cloud (AWS EC2)
UI application is deployed to the cloud (AWS S3)
Java API has 80% test coverage for service layer
Java API leverages Spring's MockMvc for integration/e2e tests of controller endpoints
Java API will be adequately documented (Java Docs and web endpoint documentation [Swagger/OpenAPI])

Getting Started:
git clone https://github.com/luisloustaunau
npm install
npm start

Back End:
https://github.com/JennicaLeClerc/Synergy_Project2_Backend.git

