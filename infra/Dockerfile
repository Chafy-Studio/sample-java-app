# Usar uma imagem base oficial do OpenJDK para Java 17
FROM openjdk:17

# Opcional: Definir o diretório de trabalho dentro do container
WORKDIR /app

# Copiar o arquivo .jar da sua aplicação Java para dentro do container
# Substitua `meuapp.jar` pelo nome real do seu arquivo .jar
COPY ./tmp/demo.jar /app/demo.jar

# Comando para executar sua aplicação Java
# Substitua `meuapp.jar` pelo nome real do seu arquivo .jar, se necessário
CMD ["java", "-jar", "/app/demo.jar"]
