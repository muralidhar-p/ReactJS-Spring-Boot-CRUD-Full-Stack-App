FROM openjdk:17-alpine
ARG JAR_FILE=code/target/*.jar
ENV NEW_RELIC_LICENSE_KEY=d9fa7f7b923f8a4d8ef9923dd67067da6d1dNRAL
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
