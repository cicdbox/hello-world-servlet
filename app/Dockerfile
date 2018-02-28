FROM tomcat

VOLUME /tmp

ADD target/helloworld*.war /usr/local/tomcat/webapps/

CMD ["catalina.sh", "run"]

EXPOSE 8080
