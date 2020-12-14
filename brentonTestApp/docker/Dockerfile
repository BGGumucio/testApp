# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine

# Copy war file
COPY brentonTestApp-0.0.1-SNAPSHOT.jar /customApp.war

# run the app
CMD ["yum -y install java"]
CMD ["/usr/bin/java", "-jar", "/customApp.war"]
