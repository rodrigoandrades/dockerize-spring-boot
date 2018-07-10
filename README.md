# dockerize-spring-boot

### Installation

```sh
$ mvn clean install
$ docker build -t app-swagger .
$ docker run -d -p 8080:8080 app-swagger
```