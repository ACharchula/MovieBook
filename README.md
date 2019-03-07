# BD2-MovieBook

Moviebook is an application about movies and artists. Moviebook allows user to browse data about movies and artists, add reviews, like reviews and rate movie. We also implemented some of the basic administrator operations. In file Documentation.pdf there is a documentation written in Polish. Not only can you find there more info about Moviebook's functionality, but also you will find there a bunch of screenshots.

Code may sometimes look chaotic and not perfectly clean. This is due to the fact that we had not enough time to refactor this project, because of deadlines.

## Backend

### Backend prerequisites

#### Java 8

To install on Ubuntu run:

`$ sudo apt install openjdk-8-jdk`

### Running backend

To run backend:

`$ cd backend`

`$ ./mvnw package`

`$ java -jar target/backend-1.0.jar`

To clean build:

`$ ./mvnw clean`

[For more amazing maven comands](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)

## Frontend

### Frontend prerequisites

#### npm

To install on Ubuntu run:

`$ sudo apt install npm`

### Running frontend

To run frontend:

`$ cd frontend`

`$ npm start`

To open frontend, go to:

`localhost:3000`
