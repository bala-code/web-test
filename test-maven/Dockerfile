FROM openjdk:8

EXPOSE 8080

ADD target/test-maven.jar test-maven.jar

ENTRYPOINT ["java","-jar","/test-maven.jar"]