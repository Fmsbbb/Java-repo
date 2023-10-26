FROM maven:3.8.4-jdk-11-slim
WORKDIR /usr/src/app
COPY . .
RUN mvn clean install
CMD ["java", "-jar", "target/your-app.jar"]
