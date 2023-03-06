FROM openjdk:8
RUN mkdir /app
WORKDIR /app
COPY target/userservice1-0.0.1-SNAPSHOT.jar /app
EXPOSE 9010 ENTRYPOINT ["java", "-jar", "userservice1-0.0.1-SNAPSHOT.jar"]