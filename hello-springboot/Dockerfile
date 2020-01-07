FROM openjdk:8-jdk-alpine
ARG REVISION
COPY target/hello-springboot-${REVISION}.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
