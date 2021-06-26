FROM openjdk:latest
ADD target/demo-mysql.jar demo-mysql.jar
EXPOSE 8086
ENTRYPOINT ["java","-jar","demo-mysql.jar"]