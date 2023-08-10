FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY  cloud-app.jar app.jar
ENTRYPOINT ["java","-jar", "--spring.profiles.active=docker", "/app.jar"]