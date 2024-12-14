# using the official OpenJDK 21 image as the base image
FROM openjdk:21-jdk
# Set the working directory in the container
WORKDIR /app
# copy app jar to the container
COPY target/*.jar gateway-service.jar
# command run the application
ENTRYPOINT ["java", "-jar", "gateway-service.jar"]