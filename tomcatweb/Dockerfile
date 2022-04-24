FROM tomcat:9.0-jre8-alpine

WORKDIR /usr/local/tomcat/webapps/

RUN wget https://github.com/alex19451/app42/blob/master/WebContent/Config.properties -P ROOT/

CMD ["catalina.sh", "run"]