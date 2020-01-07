FROM openjdk:11-jdk-slim
ARG REVISION
COPY target/hello-springboot-${REVISION}.jar app.jar
CMD ["/usr/bin/java", "-jar", "/app.jar"]
