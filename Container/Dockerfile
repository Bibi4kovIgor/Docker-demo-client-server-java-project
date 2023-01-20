FROM amazoncorretto:17.0.6
EXPOSE 8091
ARG JAR_FILE=app.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar", "app.jar"]