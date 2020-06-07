FROM tomcat:8.0
ADD /var/lib/jenkins/workspace/SamplePipelineProject/target/TestProject-1.0-SNAPSHOT.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
