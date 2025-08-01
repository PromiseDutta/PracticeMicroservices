# Start from an official OpenJDK image
FROM openjdk:21-jdk-slim


MAINTAINER "EazyBytes"

# Copy the built jar file into the container (replace with your actual jar name)
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

# Expose the port your Spring Boot app runs on (usually 8080)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]