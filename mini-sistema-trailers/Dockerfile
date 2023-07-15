FROM openjdk:8-jdk-alpine
COPY "./target/com.sistema.trailers-1.0.jar" "mini-sistema-trailers.jar"
EXPOSE 8050
ENTRYPOINT [ "java","-jar","mini-sistema-trailers.jar" ]