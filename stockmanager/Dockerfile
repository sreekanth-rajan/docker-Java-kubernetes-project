FROM openjdk:8-jre
ADD target/stockmanager-0.0.1-SNAPSHOT.jar app.jar
ADD stock-manager.yml app-config.yml
EXPOSE 8030
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
