## Spring-boot-webapp

This is a Sprint boot web application that has been built using Maven.

Follow the link for referrence: https://spring.io/guides/gs/spring-boot/

### Instructions to run this project locally

- Clone this project using the command
```bash
git clone https://github.com/sumitNITS/Spring-boot-webapp.git
```
- Run the commands to get started with the application
```
mvn clean package
```
```
java -jar target/spring-boot-webapp.jar
```

Now visit the URL http://127.0.0.1:8081/ and explore the application 🚀

### Instructions to run this project using dockerhub image

- Access the application using the command 
```bash
docker run -d -p <port>:8081 --name spring-boot-webapp sumit0058/springbootwebapp
```

Now access the application using "localhost":"port" OR "ip-of-machine":"port" 🚀

