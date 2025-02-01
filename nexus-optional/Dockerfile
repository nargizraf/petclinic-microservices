FROM openjdk:11-jre
ENV SPRING_PROFILES_ACTIVE docker,mysql
COPY admin.jar /app.jar
EXPOSE 9090
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]