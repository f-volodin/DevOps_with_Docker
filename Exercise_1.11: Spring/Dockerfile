FROM openjdk:11

COPY /material-applications/spring-example-project /usr/src/myapp
WORKDIR /usr/src/myapp

RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]

EXPOSE 8080