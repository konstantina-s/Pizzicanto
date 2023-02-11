FROM openjdk:19
WORKDIR /app
COPY target/Pizzicanto-0.0.1-SNAPSHOT.jar /app/Pizzicanto-0.0.1-SNAPSHOT.jar
COPY data.csv /app/data.csv
CMD ["java", "-jar", "Pizzicanto-0.0.1-SNAPSHOT.jar"]