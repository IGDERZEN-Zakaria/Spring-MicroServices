# Spring-MicroServices
Microservices and Distributed Systems

# Prerequisites

In order to run the application, you need to have:
1. JDK 17 (https://www.oracle.com/java/technologies/downloads/)
2. Maven 3.8.6 (https://maven.apache.org/download.cgi).
3. Git (https://git-scm.com/downloads)
   You also need to configurate your user and system path variables for both java and maven. You also need to have git installed in order to clone the project .


### Run it locally
1. Open terminal and clone the repo:
```shell
git clone https://github.com/IGDERZEN-Zakaria/Spring-MicroServices.git
```
1. Make sure you are in project directory  in order to build and package the application with the following Cmd Commande:
```shell
mvn clean install
```
1. launch the docker compose containers 
```shell
docker compose up -d
```

1. launch the microservices applications


# Architecture

![img.png](img.png)