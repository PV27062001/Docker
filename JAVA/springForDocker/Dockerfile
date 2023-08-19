FROM eclipse-temurin:17-jdk-alpine

VOLUME /tmp

WORKDIR /app

EXPOSE 8080

COPY build/libs/springForDocker-0.0.1-SNAPSHOT.jar springForDocker.jar

ENTRYPOINT ["java","-jar","springForDocker.jar"]


#docker commands

#docker build -t spring .

#docker run -p 8080:8080 -d spring

#http://localhost:8080/message  // local host link