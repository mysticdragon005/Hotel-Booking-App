FROM openjdk:14-jdk-alpine
MAINTAINER upgrad
ADD ./target/notificationService.jar /opt/app/notificationService.jar
WORKDIR /opt/app
ENV PATH="${PATH}:${JAVA_HOME}/bin"
EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "/opt/app/notificationService.jar"]