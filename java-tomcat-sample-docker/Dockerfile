FROM tomcat:8.0
COPY /var/lib/jenkins/workspace/Deploy Application with Docker Image/java-tomcat-sample/target/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
