# Maven Web Project

A simple Maven web application using JSP and a Jakarta Servlet.

## Requirements
- Java 17+
- Maven
- Apache Tomcat 10.1+

## Build
```bash
mvn clean package
```

The WAR file will be created at `target/MavenWeb.war`.

## Run
1. Copy `target/MavenWeb.war` into Tomcat's `webapps` folder.
2. Start Tomcat.
3. Open `http://localhost:8080/MavenWeb/`.
4. Enter a name and submit.
