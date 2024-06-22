FROM openjdk:17-jdk-slim 

WORKDIR /app

COPY spring-api/DKapi.jar app.jar

EXPOSE 8080

ENV DB_HOST=postgres
ENV DB_PORT=5432
ENV DB_USER=admin
ENV DB_PASSWORD=admin

ENTRYPOINT ["java", "-jar", "app.jar"]
