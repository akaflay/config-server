# Config Server

This project is used to Externalize the application properties from the project to some git repo.

With microservices architecture, we can have a central config server where we have all the configurable parameters of different Micro Services. The benefit of a central config server is that if we change a property for a microservice, which will reflect on fly even without redeploying the microservice.


Basic requirements
1. Java 8. For windows users setup Java https://www.mkyong.com/java/how-to-set-java_home-on-windows-10/
2. Maven. For windows users setup maven https://www.mkyong.com/maven/how-to-install-maven-in-windows/

Run Project.
1. Build the project using mvn clean install command.
2. Change the configuration of the DB in the application.properties in the src/main/resource folder.
3. mvn spring-boot:run
4. Make a GET request to http://localhost:8888/app/default (If no changes has been made to the application.properties files)

For any Questions and Concerns please connect with me at https://better-coder.slack.com/
