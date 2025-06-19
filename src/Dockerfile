# Pull a base image which gives all required tools and libraries
FROM openjdk:17-jdk-alpine

# Create a folder where the app code will be stored
WORKDIR /app

# Copy the source code from your HOST machine to your container 
COPY src/Main.java /app/Main.java

# Conpile the application code 
RUN javac Main.java

# Run the application 
CMD ["java", "main"]
