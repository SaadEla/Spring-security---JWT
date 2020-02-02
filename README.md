# Spring-security---JWT

## Resume

* Provide an authentication and logout for the users.
* When authentication done we have an employee CRUD

## Built With

* 	[Maven](https://maven.apache.org/) - Dependency Management
* 	[Spring Boot](https://spring.io/projects/spring-boot) - Framework to ease the bootstrapping and development of new Spring Applications
* 	[git](https://git-scm.com/) - Free and Open-Source distributed version control system 

## External Tools Used

* [Postman](https://www.getpostman.com/) - API Development Environment (Testing Docmentation)



## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.arc.sbtest.SBtemplateApplication` class from your IDE.

- Download the zip or clone the Git repository.
- Unzip the zip file (if you downloaded one)
- Open Command Prompt and Change directory (cd) to folder containing pom.xml
- Open Eclipse 
   - File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
   - Select the project
- Choose the Spring Boot Application file (search for @SpringBootApplication)
- Right Click on the file and Run as Java Application

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```





### URLs

|  URL |  Method | Remarks |
|----------|--------------|--------------|
|`http://localhost:8080/authenticate`                            | POST | For authentication|
|`http://localhost:8080/employees/1`                              | DELETE | Delete an employe|
|`http://localhost:8080/emmployees`                              | POST | Add employee|
|`http://localhost:8080/employees`                              | GET | Get all employee |





## Files and Directories

The project (a.k.a. project directory) has a particular directory structure. A representative project is shown below:

```
.
├── Spring Elements
├── src
│   └── main
│       └── java
│           ├── com.javainuse
│           ├── com.javainuse.config
│           ├── com.javainuse.controller
│           ├── com.javainuse.model
            ├── com.javainuse.service

├── src
│   └── main
│       └── resources
│           ├── application.properties
├── src
│   └── test
│       └── java
├── JRE System Library
├── Maven Dependencies
├── src
├── target
├── pom.xml
```


  
## Resources

* [Javainuse](https://www.javainuse.com/spring/ang7-jwt)
* [HTTP Status Codes](https://www.restapitutorial.com/httpstatuscodes.html)

