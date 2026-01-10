# Use OpenJDK base image
FROM eclipse-temurin:8u472-b08-jre-alpine-3.23    # Full JDK via Eclipse Temurin


WORKDIR /app

COPY target/java-jenkins-docker-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
