FROM maven:latest

WORKDIR /app

COPY . .

RUN mvn package

CMD ["java", "-jar", "target/notify_rabbitmq.jar"]