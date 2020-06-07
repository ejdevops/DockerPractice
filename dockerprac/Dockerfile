FROM tomcat:8.0
RUN sudo cp -a /var/lib/jenkins/workspace/SamplePipelineProject/target/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
