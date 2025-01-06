# Usar a imagem base OpenJDK
FROM openjdk:17-jdk-slim

# Criar um diretório para o aplicativo
RUN mkdir /app

# Definir o diretório de trabalho
WORKDIR /app

# Copiar o JAR gerado para o contêiner
COPY target/securing-web-complete-0.0.1-SNAPSHOT.jar /app/app.jar

# Expor a porta usada pelo Spring Boot
EXPOSE 8080

# Comando para executar o aplicativo
CMD ["java", "-jar", "/app/app.jar"]
