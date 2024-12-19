# Use a lightweight Java 17 base image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy your JAR file into the container
COPY demo-0.0.1-SNAPSHOT.jar /app/app.jar

# Expose the application port (default Spring Boot port is 8080)
EXPOSE 8080

# Run the JAR file
CMD ["java", "-jar", "/app/app.jar"]


