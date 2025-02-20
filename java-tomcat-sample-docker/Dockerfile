FROM ubuntu:latest
RUN apt install tomcat9
COPY **/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
