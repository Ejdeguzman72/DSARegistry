FROM amazoncorretto:17
WORKDIR /app
COPY /target/dsa-eureka-server-0.0.1-SNAPSHOT.jar /app/dsa-eureka-server-0.0.1-SNAPSHOT.jar
EXPOSE 8761
CMD ["java", "-jar", "dsa-eureka-server-0.0.1-SNAPSHOT.jar", "--server.port=8761"]