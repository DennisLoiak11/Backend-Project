# Usa un'immagine di base con Java e un sistema operativo leggero
FROM openjdk:17

WORKDIR /app

# Copia il tuo file JAR Spring Boot nell'immagine
COPY todoApp-0.0.1-SNAPSHOT.jar app.jar

# Porta su cui l'applicazione sarà esposta
EXPOSE 8081

# Comando per avviare l'applicazione
CMD ["java", "-jar", "app.jar"]






