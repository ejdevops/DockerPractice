FROM tomcat:8.0
RUN cp /var/lib/jenkins/workspace/SamplePipelineProject/target/TestProject-1.0-SNAPSHOT.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
