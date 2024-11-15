Description:
This repository contains a simple Spring Boot application that implements a partial "Blood Bank Information System." The app handles seeker, blood bank, and blood stock information through RESTful services. It uses in-memory storage (List or Map) for data persistence, with no JPA implementation required.

Key components:

Seeker (Patient) Information Management: Including details like first name, last name, age, blood group, city, and phone.
Blood Bank Management: Stores blood bank details like name, address, city, phone, and email.
Blood Stock Tracking: Manages blood group, quantity, best-before date, and stock status.
This system exposes RESTful APIs for:

GET: Retrieve information for each entity.
POST: Add new records for seekers, blood banks, and blood stock.
PUT: Update existing records.
DELETE: Remove records.
The application integrates Spring Boot, Thymeleaf templates, and standard Spring MVC practices. It runs on Tomcat Apache server on port 8080 and can be tested using POSTMAN.

Feel free to explore the project and test the APIs with REST clients like POSTMAN.
