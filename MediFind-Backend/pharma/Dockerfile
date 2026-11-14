FROM amazoncorretto:17-al2023-jdk

RUN pwd

WORKDIR /app

RUN pwd

COPY target/pharma-0.0.1-SNAPSHOT.jar /app/medifind.jar

EXPOSE 8080

ENTRYPOINT ["java", "-Dspring.profiles.active=prod", "-jar", "medifind.jar"]
