# Use a base image with Java runtime
FROM eclipse-temurin:21.0.4_7-jre-alpine
 
# Create a directory for the app
WORKDIR /app
 
# Copy the JAR file into the container
COPY ./*.jar /app/copilot-agent-demo-customer.jar
 
# provide a hook into the webapp
EXPOSE 8080
 
# run the application
ENTRYPOINT ["java", "-jar", "copilot-agent-demo-customer.jar"]
