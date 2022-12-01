# 🚖Taxi-Service🚖
#### This is a web-application that supports authentication, registration and CRUD operations, based on SOLID principles.
# Features:
➩ registration as a driver,

➩ login as a driver.

#### After successful authentication you can:
➩  create / update / remove:
* a car,
* a driver,
* a manufacturer ;

➩ add driver to car;

➩ remove driver from a car;

➩ display a list of all:
* cars,
* drivers,
* manufacturers.
## Structure:
#### The project uses a three-level architecture:

| **Controllers**  |
|:----------------:|
|        ⇕         |
|   **Services**   |
|        ⇕         |
|     **DAO**      |
## Technologies:
* Java,
* Maven,
* JDBC,
* MySQL,
* Tomcat,
* Servlet,
* JSP,
* JSTL,
* HTML, CSS.
## How to run the project:
* clone this project,
* run the script from src/main/resources/init_db.sql into MySQL,
* configure src/main/java/taxi/util/ConnectionUtil.java with your URL, USERNAME, PASSWORD, JDBC_DRIVER,
* configure and run Tomcat.
