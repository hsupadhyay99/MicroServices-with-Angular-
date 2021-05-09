# Course Enrollment Microservices, Spring Cloud, Spring Boot, Angular 8, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **microservice-user-management** - Microservice implemented using Spring boot. (microservice-user-management/README.md)
- **microservice-course-management** - Microservice implemented using Spring boot. (microservice-course-management/README.md)
- **eureka-discovery-service** - Microservice implemented using Spring eureka. (eureka-discovery-service/README.md)
- **zuul-gateway-service** - Microservice implemented using Spring zuul. 
(zuul-gateway-service/README.md)
- **client-side** - A NodeJs application implemented using Angular 8. This consumes services hosted by server side. 

### Build

#### 1) Build Spring Boot microservices
   
```
$ cd microservice path
$ gradlew bootJar
$ gradlew bootRun
```

#### 2) Build and run client side application

```
$ cd client-side
$ npm install
$ ng serve
```

### Access application using following URL

```
http://localhost:4200
```
