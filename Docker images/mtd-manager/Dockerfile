FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
#ENV DB_URL jdbc:postgresql://192.168.122.172:5432/cloud
#ENV DB_USER mtdmanager
#ENV DB_PASSWORD mtdmanager
COPY  mtd-manager-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar", "--spring.profiles.active=docker", "/app.jar"]