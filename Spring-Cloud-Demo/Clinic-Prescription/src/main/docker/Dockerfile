#获取base image
FROM adoptopenjdk/openjdk8:latest
VOLUME /opt/tmp
ADD *.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8005
