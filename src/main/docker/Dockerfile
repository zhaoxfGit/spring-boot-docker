FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD spring-boot-docker-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]