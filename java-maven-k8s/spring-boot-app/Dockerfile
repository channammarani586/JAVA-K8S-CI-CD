FROM adoptopenjdk/openjdk11:alpine-jre

# Define the artifact path
ARG artifact=target/hello-world-1.0.jar

WORKDIR /opt/app

# Copy the built JAR file to the container
COPY ${artifact} app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
