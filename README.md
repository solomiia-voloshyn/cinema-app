# Cinema App web project 🎬

## 📝 Description:
 Back-end Cinema App web application was built using Spring & Hibernate frameworks.
 It allows users to send HTTP requests:GET, PUT, POST, DELETE.Web app supports user authentication, authorization and CRUD operations.

## 🎥 Main technologies used:
Java 17, Spring Web MVC, Spring Security, Hibernate, MySQL, Tomacat@9, Maven

## 📽️ Functional app schema:
Schema shows current app functionality for better understanding:
<img src="img.png" width="75%"/>

## 📋 Roles Endpoints:

* DELETE: /movie-sessions/{id} - (admin)
* GET: /cinema-halls - (user/admin)
* GET: /movies - (user/admin)
* GET: /movie-sessions/available - (user/admin)
* GET: /orders - (user)
* GET: /shopping-carts/by-user - (user)
* GET: /users/by-email - (admin)
* POST: /register - (all)
* POST: /cinema-halls - (admin)
* POST: /movies - (admin)
* POST: /movie-sessions - (admin)
* POST: /orders/complete - (user)
* PUT: /movie-sessions/{id} - (admin)
* PUT: /shopping-carts/movie-sessions - (user)

## 🖨️ Project structure:

N-tier architecture with Spring

* @Controller: the presentation tier
* @Service: the application logic tier
* @Repository: the data tier

## 📺 How to install the app:
1. Install Intellij, JDK 17, MySQL and TomCat@9 on your computer (if you don't have some already);
2. Clone this repo to you IDE and open it;
3. Link your MySql database: replace username, password, driver and url in resources/db.properties with your own;
4. Add Tomcat@9 configuration;
5. Run "mvn clean package" command in terminal;
6. Start Tomcat and try app.

P.s. You can use Postman for running http requests for better experience