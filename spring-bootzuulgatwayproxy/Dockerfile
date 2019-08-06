FROM openjdk:11

COPY target/spring-bootzuulgatwayproxy-0.0.1-SNAPSHOT.jar gatway.jar

EXPOSE 8092

RUN sh -c 'touch gatway.jar'

ENTRYPOINT ["java","-jar","gatway.jar"]