FROM openjdk:8-jre-alpine
ADD target/ /opt/
WORKDIR /opt
EXPOSE 10002
ENTRYPOINT exec java -Xms128m -Xmx128m $JAVA_OPTS -jar caller-service.jar
