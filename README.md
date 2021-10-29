# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.6.0-SNAPSHOT/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.6.0-SNAPSHOT/maven-plugin/reference/html/#build-image)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/2.5.5/reference/htmlsingle/#boot-features-jpa-and-spring-data)

### Guides
The following guides illustrate how to use some features concretely:

* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

## HOW TO US THIS PROJECT
* 0. delete all plug-ins from pom.xml file
* 1. compile the JAR -> ./mvnw install
* 2. verify the JAR -> ls ./target/springboot-commons-lib-0.0.1-SNAPSHOT.jar
* 3. update any local project entity import for the commons-lib import package
* 4. include in the main app springboot class the scan for the entities in the commons-lib package by adding @EntityScan({"com.springboot.app.commonslib.model.entity"})