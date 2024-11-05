FROM java:8

MAINTAINER chenjunxi1<chenjunxi1@xxx>

EXPOSE 8081

ARG JAR_FILE

ADD target/${JAR_FILE} /app.jar

CMD ["java", "-jar","/app.jar"]
