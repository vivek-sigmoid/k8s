FROM tomcat:9.0.54-jdk8-temurin-focal
ADD ./k8s_project_new.war /usr/local/tomcat/webapps.dist
ADD ./start.sh /usr/local/tomcat
CMD ["catalina.sh", "run"]
RUN chmod +x start.sh
RUN ./start.sh
