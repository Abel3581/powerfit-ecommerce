# Usa una imagen base de Java (elige la versión que necesites)
FROM openjdk:17

# Directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el archivo JAR de tu proyecto a la imagen
COPY target/powerfit-0.0.1-SNAPSHOT.jar /app/app.jar

# Comando para ejecutar la aplicación Spring Boot al iniciar el contenedor
CMD ["java", "-jar", "app.jar"]
