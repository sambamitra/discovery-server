[![Build Status](https://travis-ci.org/sambamitra/discovery-server.svg?branch=master)](https://travis-ci.org/sambamitra/discovery-server)
# Discovery Server
This is a Discovery Server project based on Netflix Eureka and Spring Cloud.

## Prerequisites
- JDK 1.8 or later
- Maven 3.x
- Docker - Download and install : <https://www.docker.com/products/overview>

## How to run
* Clone the project
* Build the project using : __mvn clean install -DskipDockerBuild__
* Run the component using : __java -jar discovery-server-0.1.0-SNAPSHOT.jar__
* Go to <https://localhost:8761>. This should show the Eureka dashboard with all the services registered to Eureka.

## Microservice architecture model
This project is part of an example microservice architecture model. For more details, go to [Microservice Example](https://github.com/sambamitra/microservice-example)
