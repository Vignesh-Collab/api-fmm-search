# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the target directory to the container
COPY api-fmm-search-1.0-SNAPSHOT.jar /app/api-fmm-search.jar

# Run the JAR file
CMD ["java", "-jar", "api-fmm-search.jar"]
