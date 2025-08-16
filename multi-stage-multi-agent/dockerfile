# Use official Java image
FROM openjdk:11

# Set working directory
WORKDIR /app

# Copy source code
COPY HelloWorld.java .

# Compile the Java code
RUN javac HelloWorld.java

# Run the Java program
CMD ["java", "HelloWorld"]
