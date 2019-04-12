FROM openjdk

VOLUME /tmp
ADD maven/eurekaNamingServer-0.0.1-SNAPSHOT.jar eurekaNamingServer.jar
RUN sh -c 'touch /eurekaNamingServer.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/eurekaNamingServer.jar"]
