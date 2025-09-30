FROM eclipse-temurin:21-jre

WORKDIR /opt/application
COPY ./target/*SNAPSHOT.jar backend.jar
CMD [ "java", "-jar", "backend.jar" ]
WORKDIR /opt/application