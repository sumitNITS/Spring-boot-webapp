## Spring-boot-webapp

This is a Sprint boot web application that has been built using Maven.

Follow the link for referrence: https://spring.io/guides/gs/spring-boot/

### Tools used in this project

- Git
- Maven
- Jenkins
- Sonarqube
- Docker
- Kubernetes
- Argo CD

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

### Success outputs for this project

![Dockerhub output](https://github.com/sumitNITS/Spring-boot-webapp/assets/37767537/c55cb9a9-59cb-47ff-b9a4-4bb815e750e3)

![Sonarqube output](https://github.com/sumitNITS/Spring-boot-webapp/assets/37767537/39b59200-252d-4323-8cac-604428fbe2e0)

![Jenkins Output](https://github.com/sumitNITS/Spring-boot-webapp/assets/37767537/0801e3b4-48c2-4c81-9683-17d96108a174)

![Argocd output](https://github.com/sumitNITS/Spring-boot-webapp/assets/37767537/6cc81a1e-3e19-425f-85a2-01d5f0a881df)

![K8s deployment-minikube](https://github.com/sumitNITS/Spring-boot-webapp/assets/37767537/a0af6e54-f3e7-42b8-b836-b7a4af3ae0d8)