FROM openjdk:21-slim

WORKDIR /app

COPY bff-0.0.1-SNAPSHOT.jar ./bff.jar

COPY application-docker.properties .

CMD ["java", "-jar", "bff.jar"]
