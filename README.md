## Spring Boot Practice

How to run the service and the tests

# Get the code

Git:

git clone https://github.com/Madison-White/spring-boot-practice.git
cd spring-boot-practice

Or simply download the zip file.

# Run the service

Open a command window and run:

MacOS/Linux: $ ./mvnw spring-boot:run

Windows: $ mvnw spring-boot:run

# Run the service with curl

Open a new command window and run:

$ curl localhost:8080

A response will be returned.

# Check the application status

You can check the health of the application by running the following command:

$ curl localhost:8080/actuator/health
