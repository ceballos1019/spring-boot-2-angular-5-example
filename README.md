# Basic CRUD App with Angular 5.0 and Spring Boot 2.0
 
This example app shows how to build a basic CRUD app with Spring Boot 2.0, Spring Data, and Angular 5.0.

Please read [Build a Basic CRUD App with Angular 5.0 and Spring Boot 2.0](https://developer.okta.com/blog/2017/12/04/basic-crud-angular-and-spring-boot) to see how this app was created.

**Prerequisites:** [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) and [Node.js](https://nodejs.org/).


## Getting Started

To install this example application, run the following commands:

```bash
git clone https://github.com/ceballos1019/spring-boot-2-angular-5-example
cd spring-boot-2-angular-5-example
```

This will get a copy of the project installed locally. To install all of its dependencies and start each app, follow the instructions below.

To run the server, cd into the `server` folder and run:
 
```bash
./mvnw spring-boot:run
```

To run the client, cd into the `client` folder and run:
 
```bash
npm install && npm start
```