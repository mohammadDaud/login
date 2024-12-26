FROM openjdk:11

EXPOSE 8089

ARG JAR_FILE=target/login-tutorial.jar
ADD ${JAR_FILE} login-tutorial.jar

ENTRYPOINT ["java", "-jar", "/login-tutorial.jar"]