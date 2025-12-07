# Use a lightweight Java 17 runtime image
FROM eclipse-temurin:17-jre-alpine

# Copy the JAR built by Maven into the container
COPY test/target/*.jar app.jar

# Expose the port your app listens on (optional, update if needed)
EXPOSE 8080

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app.jar"]