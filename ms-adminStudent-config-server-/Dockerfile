FROM openjdk:17
EXPOSE 8888
ADD ./target/ms-adminstudent-config-server--0.0.1-SNAPSHOT.jar   ms-adminstudent-config-server-1.jar
ENTRYPOINT ["java","-jar","-Dspring.profiles.active=docker","/ms-adminstudent-config-server-1.jar"]
