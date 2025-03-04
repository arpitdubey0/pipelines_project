# Use an official OpenJDK image as the base image
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy all Java source files to the container
COPY . /app

# Compile Java files inside the container
RUN javac Main.java

# Specify the command to run the Java application
CMD ["java", "Main"]
