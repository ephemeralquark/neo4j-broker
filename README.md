NOTE: This is work in progress, doesn not work.

Sample Spring Boot project using the [Spring Cloud - Cloud Foundry Service Broker](https://github.com/spring-cloud/spring-cloud-cloudfoundry-service-broker).

# Overview

This sample project uses the Spring Cloud - Cloud Foundry Service Broker to implement a Neo4j service. The MongoDB service also uses [spring-boot-data-neo4j](https://github.com/spring-projects/spring-boot/tree/master/spring-boot-starters/spring-boot-starter-data-neo4j) to persist service instances and bindings.

## Getting Started

You need to install and run Neo4j somewhere and configure connectivity in [application.properties](src/main/resources/application.properties).

Build it:

    ./gradlew build

After building, you can push the broker app to Cloud Foundry or deploy it some other way and then [register it to Cloud Foundry](http://docs.cloudfoundry.org/services/managing-service-brokers.html#register-broker).



