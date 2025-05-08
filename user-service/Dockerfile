FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/user-service-0.0.1-SNAPSHOT.jar user-service.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "user-service.jar"]