# 🚖Taxi-Service🚖
#### This is a web-application that supports authentication, registration and CRUD operations, based on SOLID principles.
## Features:
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
* clone [this](https://github.com/Serhii-Prykhodko/taxi-service) project,
* install [MySQL](https://dev.mysql.com/downloads/installer/) and run the script from [src/main/resources/init_db.sql](https://github.com/Serhii-Prykhodko/taxi-service/blob/main/src/main/resources/init_db.sql), ,
* configure [src/main/java/taxi/util/ConnectionUtil.java](https://github.com/Serhii-Prykhodko/taxi-service/blob/main/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER,
* install [Tomcat 9.0.50](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) configure and run.
