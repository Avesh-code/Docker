# this is a base of the application  
FROM eclipse-temurin:17-alpine

# to create a directory in container
WORKDIR /app

# to copy the source code from local to container directory
COPY src/Main.java /app/Main.java

# to compilke the code 
RUN javac Main.java

# to run the java application
CMD ["java", "Main"]

