FROM alpine

RUN apk add openjdk17

COPY ./messages-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT [ "java","-jar","/app.jar" ]