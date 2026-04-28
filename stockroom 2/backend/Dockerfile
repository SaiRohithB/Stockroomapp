FROM maven:3.9.9-eclipse-temurin-17 AS mavenbuild
WORKDIR /app
COPY . .
RUN mvn clean package
FROM eclipse-temurin:17-jre
WORKDIR /app
COPY --from=mavenbuild /app/target/*.jar app.jar
EXPOSE 8080
CMD ["java","-jar","app.jar"]                      