# Use an official OpenJDK image as the base image
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy all Java source files to the container
#COPY myapp.jar myapp.jar

#CMD ["java", "-jar", "myapp.jar"]

#CMD ["java", "TestingProject/bin/com/nishkaiv/TestingClass.java"]

COPY myapp.jar myapp.jar 

# Expose the application port (change this if your app uses a different port)
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "myapp.jar"]

