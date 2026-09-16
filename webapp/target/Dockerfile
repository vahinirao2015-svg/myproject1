FROM tomcat:10.1-jdk21

RUN rm -rf /usr/local/tomcat/webapps/*

COPY *.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8081

CMD ["catalina.sh", "run"]
