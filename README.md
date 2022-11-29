# 🚕Taxi-service🚖
## <h>☕Short description</h>
It's a simple web-application which follows SOLID and also build according to N-tier architecture patterns.
This project implements such ability as authorization, registration and non-access to some
resources by non-authorized users by using filters. Methods of working with databases, namely CRUD, are also shown.
Here we have 4 layers: GUI, business layer, persistence layer, database layer

## <h>📋Features</h>
* Registration as a driver
* Authentication a driver. Only authenticated driver can use functional capabilities
* Display all drivers / cars / manufacturers
* Display all Cars by Driver
* Create new driver / dar / manufacturer
* Soft delete driver / car / manufacturer
* Display all cars for user that was authenticated
* Add drivers to car

## <h>🧠Project structure</h>
<strong><i>&nbsp;&nbsp;&nbsp;3-layer architecture</i></strong>
* Presentation layer - controllers
* Application layer - services
* Data access layer - DAO

## <h>🛠Technologies</h>
* <a href="https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html">JDK 11</a>
* Maven 4.0
* <a href="https://dev.mysql.com/downloads/mysql/">MySQL 8.0.22</a>
* <a href="https://tomcat.apache.org/download-90.cgi">TomCat 9.0.50</a>
* Java Servlet API 4.0.1
* JSTL 1.2
* JDBC
* JSP

## <h>👌How to start the program</h>
1️⃣Install <a href="https://tomcat.apache.org/download-90.cgi"><i>TomCat version 9.0.50</i></a>
and <a href="https://dev.mysql.com/downloads/mysql/"><i>MySQL</i></a>\
2️⃣Clone the project from GitHub\
3️⃣Use <i>init_db.sql</i> to create a schema and tables\
4️⃣Configure <i>ConnectionUtil</i> with your own parameters\
5️⃣Configure <i>TomCat</i> for this project\
6️⃣For confidence you can run in console <i>mvn clean package</i> 
