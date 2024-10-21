FROM openjdk:17-jdk-slim

WORKDIR /calc

COPY . /calc/

RUN javac game.java

ENTRYPOINT [ "java", "game" ]

