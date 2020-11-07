FROM openjdk:8
RUN mkdir -p /app/
ADD build/libs/eurekaserver-0.0.1-SNAPSHOT.jar /app/eurekaserver-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/app/eurekaserver-0.0.1-SNAPSHOT.jar"]