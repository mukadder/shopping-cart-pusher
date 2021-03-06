# shopping-cart-pusher

This web application shows you how to program a simple shopping cart in React with a Java backend, using Pusher to add realtime features.

The stack:

- Java 8
- Maven as the build manager
- Spring Boot with Spring MVC as the server-side framework
- React in the front-end

# Requirements

- [A Pusher account](https://pusher.com/)
- [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven](https://maven.apache.org/download.cgi)

# Installation
1. Clone this repository and `cd` into it.
6. Start the application with one of the following commands (if you're using an IDE like Eclipse, just run the class `com.pusher.ShoppingCartApplication`):

    ```
    mvn spring-boot:run
    ```
    
    Or
    
    ```
    mvn package -DskipTests
    java -jar target/shopping-cart-0.0.1-SNAPSHOT.jar 
    ```
    
7. Go to `http://localhost:8080` and start playing with the app
 

# License
MIT
