FROM openjdk:8u171-jdk-alpine3.7
ARG REVISION
COPY target/hello-springboot-${REVISION}.jar app.jar
CMD ["/usr/bin/java", "-jar", "/app.jar"]
