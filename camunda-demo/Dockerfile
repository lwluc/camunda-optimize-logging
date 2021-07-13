FROM  maven:3-jdk-8 as build
WORKDIR /app
COPY . /app
RUN mvn clean package -B

EXPOSE 8080
ENTRYPOINT ["java","-jar","target/camunda-demo.jar"]