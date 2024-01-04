FROM clearpursuitdocker/tomcat9-jdk11-lite
ENV VIRTUAL_HOST=www.petmeetsworld.com
ADD server.xml /usr/local/tomcat/conf
ADD PMW.war /usr/local/tomcat/webapps
WORKDIR /usr/local/tomcat
EXPOSE 8080