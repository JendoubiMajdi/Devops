FROM openjdk:11-jdk-alpine

# Expose port 8083 for the application
EXPOSE 8083

# Add the JAR file to the Docker image
ADD target/eventsProject-1.0.0.jar eventsProject-1.0.0.jar

# Specify the entry point for the Docker container
ENTRYPOINT ["java", "-jar", "/eventsProject-1.0.0.jar"]
