# Use Eclipse Temurin JDK 21 base image
FROM eclipse-temurin:21-jdk-alpine

# Set working directory in the container
WORKDIR /hello-world

# Copy the JAR file into the container
COPY target/docker-prac-v1.jar hello-world.jar

# Expose the port your Spring Boot app runs on (typically 8080)
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "hello-world.jar"]
