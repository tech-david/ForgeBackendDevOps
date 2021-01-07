# Alpine Linux with OpenJDK JRE
FROM openjdk:8-jre-alpine

# Copy war file
COPY Portfolio-Review-Service-0.0.1-SNAPSHOT.war /forge.war

# run the app
CMD ["/usr/bin/java", "-jar", "/forge.war"]