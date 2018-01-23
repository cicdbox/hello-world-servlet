FROM tomcat

VOLUME /tmp

#ADD target/conference-app*.war app.war

ADD target/helloworld*.war /usr/local/tomcat/webapps/
#RUN bash -c 'touch /app.war'

#ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.war"]

CMD ["catalina.sh", "run"]

EXPOSE 8080
