FROM militer/opencv-java-base
VOLUME /tmp
ADD image-service-1.0-SNAPSHOT.jar app.jar
EXPOSE 8081
RUN sh -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
