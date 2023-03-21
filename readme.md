
# Swagger Demo

This is a demo project to show how to use Swagger with Spring Boot. This version of swagger is now compatible with Spring Boot 3.0.4

## How to run

1. Clone the project
2. Launch the application
   - From your VS Code: `Run` -> `Start Debugging`
   - From the command line: `mvn spring-boot:run`
3. Open swagger on <http://localhost:8080/swagger-ui/index.html>

The dependency to add to your pom.xml is:

```xml
<dependency>
  <groupId>org.springdoc</groupId>
  <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
  <version>2.0.0</version>
</dependency>
```
