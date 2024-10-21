FROM openjdk:17-jdk-slim

COPY ./calc.java /tmp 

WORKDIR /tmp 

RUN javac calc.java

ENTRYPOINT [ "java", "calc" ]

