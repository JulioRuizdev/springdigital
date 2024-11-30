FROM openjdk:17-jdk-slim
# Definir el nombre del archivo .jar como un argumento
ARG JAR_FILE=target/skyblue-hotel-0.0.1.jar

# Copiar el archivo .jar desde la ruta especificada al contenedor
COPY ${JAR_FILE} app_skyblue_hotel.jar

# Exponer el puerto en el contenedor
EXPOSE 8080

# Comando de inicio de la aplicación
ENTRYPOINT ["java", "-jar", "app_skyblue_hotel.jar"]
