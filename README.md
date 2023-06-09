# 🚖 TAXI-SERVICE 🚖



👀  `Description:`

**A simple web-application that supports authentication, registration and CRUD operations with all entities.**


`📌  Features:`

* registration as a driver;
* authentication as a driver;
* create/update/remove a manufacturer;
* create/update/remove a car;
* create/update a driver;
* display list of all manufacturers;
* display list of all cars;
* display list of all drivers;
* display list of all cars by current driver;
* add driver to car.


`📐 Architecture`

`Project structure (3-layer architecture):`

* DAO - Data access layer
* Service - Application logic layer
* Controllers - Presentation layer



`📝  Used technologies and libraries:`

* Java 11
* Git
* Apache Maven
* Apache Tomcat
* MySQL
* JDBC
* Javax Servlet
* JSP
* JSTL
* HTML/CSS
* Log4j
* Checkstyle plugin



`💻  Steps to run the app:`

* Clone [this](https://github.com/AVykhovanok/taxi-service) repo;
* Install MySQL;
* Configure Apache Tomcat version: 9.0.74;
* Copy and run SQL script /src/main/resources/init_db.sql to creating a schema and tables for the project;
* Configure /src/main/java/taxi/util/ConnectionUtil.java with your URL, USERNAME, PASSWORD, JDBC_DRIVER;

`🚀  Run and use application!  ` 