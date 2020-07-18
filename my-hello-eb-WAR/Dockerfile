FROM openjdk:8-jdk-alpine
EXPOSE 5000
#ADD target/*.war app.war
COPY ./target/hello.war hello.war 
ENTRYPOINT ["java","-jar","hello.war"]