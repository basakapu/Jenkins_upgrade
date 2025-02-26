FROM tomcat:9.0
COPY /var/lib/jenkins/workspace/Deploy Application with Docker Image/java-tomcat-sample/target/ /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
