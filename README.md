# Spring Boot & Docker

whiteship님의 스프링부트와 도커 연결 방송 실습 프로젝트
* [Youtube Link](https://www.youtube.com/watch?v=agbpWm2Ho_I)
* [Spring guide](https://spring.io/guides/gs/spring-boot-docker/)

## Requirements
* Java 8
* maven
* Docker

## Run
```
$ docker run -d -p 10001:8080 hanras/spring-docker
$ curl localhost:8080 
```
