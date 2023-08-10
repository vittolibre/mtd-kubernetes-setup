FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
ENV DB_URL jdbc:postgresql://192.168.1.11:5432/edgegateway
ENV DB_USER edgegatewayadmin
ENV DB_PASSWORD edgegateway
ENV MQTT_SERVER_HOST 192.168.1.11
ENV MQTT_SERVER_PORT 1883
ENV MQTT_CLIENT_ID gateway1
COPY  edge-gateway-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
