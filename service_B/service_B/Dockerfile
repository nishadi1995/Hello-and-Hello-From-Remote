FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/service_B-0.0.1-SNAPSHOT.jar app2.jar
ENTRYPOINT ["java","-jar","/app2.jar"]