
# Use openjdk:11.0.2-jre-slim as the base image
FROM openjdk:11.0.2-jre-slim

# Expose the service on port 8080
EXPOSE 8080

# Copy the JAR file into the container
COPY api-gateway-0.0.1-SNAPSHOT.jar /app.jar

# Command to run the JAR file
CMD ["java", "-jar", "/app.jar"]
