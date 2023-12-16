FROM openjdk:8
EXPOSE 8085
ADD target/spring-boot-mongodb-0.0.1-SNAPSHOT /product.jar
ENTRYPOINT ["java","-jar","/product.jar"]