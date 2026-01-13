FROM openjdk:21-ea-slim
LABEL authors="maslyak"
WORKDIR /app

COPY target/Customary-demo.jar /app/app.jar

ENTRYPOINT ["java", "-jar", "/app/app.jar"]