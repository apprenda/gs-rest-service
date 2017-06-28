FROM openjdk:8-jre-alpine
COPY target/gs-rest-service-0.1.0.war /gs-rest-service-0.1.0.war

ENTRYPOINT ["java", "-jar", "-Djava.security.egd=file:/dev/./urandom", "/gs-rest-service-0.1.0.war"]
