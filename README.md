# Camel Swagger Java example

### Introduction
This is an example that uses the rest-dsl to define a rest services which provides three operations

- GET user/{id}     - Find user by id
- PUT user          - Updates or create a user
- GET user/findAll  - Find all users

The example also embeds the swagger ui.

### Build
You will need to compile this example first:

`mvn compile`

### Compile
To run the example type

`mvn jetty:run`

The example is built as a WAR which can also be deployed in a WAR container such as Apache Tomcat.

The example has documentation in the home.html page which you can access using the following url

<http://localhost:8080/camel-swagger-svc/>

This example implements the rest-dsl in Java.

To stop the example hit `ctrl + c`
