# config-server

This project is basically a server that helps to externalize all out poperties to outside the project.

Basic requirements

1. Java 8. For windows users setup Java https://www.mkyong.com/java/how-to-set-java_home-on-windows-10/
2. Maven. For windows users setup maven https://www.mkyong.com/maven/how-to-install-maven-in-windows/

Run Project.

1. Build the project using mvn clean install command.
2. Change the configuration of the DB in the application.properties in the src/main/resource folder.
3. mvn spring-boot:run
4. Make a GET request to http://localhost:8888/app/default (If no change made to the config repo)

For any Questions and Concerns please connect with me at https://better-coder.slack.com/
