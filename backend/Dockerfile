FROM openjdk:8-jdk-alpine
ADD ./target/*.jar app.jar
EXPOSE 8082
ENTRYPOINT [ "java", "-jar", "app.jar"]