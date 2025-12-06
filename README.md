#  Technical Blog Application

A simple Spring Boot--based web application for managing and displaying
blog posts.

## Overview

The **Technical Blog Application** is a classic Spring Boot MVC
project that demonstrates how to build a full-stack web application
using:

* Spring Boot (2.0.5) 
* Spring MVC 
* JSP views 
* Embedded Tomcat 
* Simple Controller--Service--Model structure

The app starts on
http://localhost:8080 and displays
all blog posts on the home page (\`HomeController\`).



##  Features

* Display list of blog posts on the home page 
* MVC layered architecture 
* JSP-based UI 
* Embedded Tomcat (no external server needed) 
* Easy to build and run with Maven 


## How to Run the Application

 __Prerequisites__

* Java **8** (required because Spring Boot 2.0.5 uses older CGLIB)
* Maven installed (\`mvn -v\`) 
* Eclipse or IntelliJ (optional)



__Run with Maven (Recommended)__

\`\`\`bash mvn clean install || mvn spring-boot:run \`\`\`



__Run the Generated JAR__

\`\`\`bash java -jar target/TechnicalBlogApplication-0.0.1-SNAPSHOT.jar\`\`\`

__Access the Application__

Open:   http://localhost:8080




## Summary

This project is a lightweight Spring Boot blogging demo ideal for
learning:

* MVC web development 
* Controller → Service → View flow 
* How Spring Boot auto-configures web applications 
* Running JSP-based apps on embedded Tomcata
