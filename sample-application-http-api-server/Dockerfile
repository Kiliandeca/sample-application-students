# Run
FROM openjdk:11-jre-slim
ENV MYAPP_HOME /opt/app
WORKDIR $MYAPP_HOME
COPY ./target/*-exec.jar $MYAPP_HOME/app.jar

EXPOSE 8080

ENTRYPOINT java -jar myapp.jar
