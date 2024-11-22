FROM openjdk:17.0.1-jdk-slim
VOLUME [ "/tmp" ]
WORKDIR /apps
ADD target/*.jar .
ENTRYPOINT [ "java","-jar","health-check.jar" ]