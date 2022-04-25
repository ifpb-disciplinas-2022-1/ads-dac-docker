FROM tomcat
RUN mkdir /usr/local/dados
VOLUME [ "/usr/local/dados" ]
COPY a.txt /usr/local/dados
COPY app.war ${CATALINA_HOME}/webapps
