FROM eclipse-temurin:21-jdk-alpine

LABEL version="1.0.1"

WORKDIR /testdir/java

COPY . .

RUN javac calc.java

CMD ["java", "calc"]
