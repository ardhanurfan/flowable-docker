FROM tomcat:8.5.5-jre8

COPY conf/tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml

COPY webapps/flowable-rest.war /usr/local/tomcat/webapps/
COPY webapps/flowable-ui.war /usr/local/tomcat/webapps/

EXPOSE 8080

WORKDIR /usr/local/tomcat
