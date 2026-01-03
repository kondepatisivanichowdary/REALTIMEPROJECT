FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/mcapp-1.0.0.war app.war
EXPOSE 8080
CMD ["java", "-jar", "app.war"]
