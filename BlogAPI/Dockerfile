FROM openjdk:17-alpine
ADD target/blog-api-docker.jar blog-api-docker.jar
ENTRYPOINT ["java", "-jar","blog-api-docker.jar"]
EXPOSE 8080