FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/skyblue-hotel-0.0.1.jar
COPY ${JAR_FILE} app_skyblue_hotel.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_skyblue_hotel.jar"]