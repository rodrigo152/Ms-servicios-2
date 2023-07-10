FROM openjdk:17
EXPOSE 8889
ADD ./target/ms-admin-registry-server--1-0.0.1-SNAPSHOT.jar   ms-admin-registry-server--2.jar
ENTRYPOINT ["java","-jar","-Dspring.profiles.active=docker","/ms-admin-registry-server--2.jar"]