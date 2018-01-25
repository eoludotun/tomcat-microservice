# tomcat-microservice
Project from [Oracle tutorial using embedded Tomcat.](http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/basic_app_embedded_tomcat/basic_app-tomcat-embedded.html)

To build and run the project on a Linux system:

1. Clone this repo:

      git clone http://github.com/tomlamphier/tomcat-microservice.git

2. Use Maven to build it:

      mvn clean package

3. Change to *target* directory, enter command:

      java -jar employees-app-1.0-SNAPSHOT-jar-with-dependencies.jar

4. Go to home page of app by typing *localhost:8080* in your browser address. 
