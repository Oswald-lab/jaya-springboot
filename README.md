# 02-java-springboot-app
Spring Boot 3.2.5 (Java 17) with `@SpringBootApplication` main class `DemoApplication`,
`pom.xml` AND `build.gradle` in root.

Maven:  mvn spring-boot:run   |  mvn package && java -jar target/springboot-app-1.0.0.jar
Gradle: ./gradlew bootRun     |  ./gradlew bootJar
Then:   curl http://localhost:8080/hello   ->  {"message":"Hello from Spring Boot"}
