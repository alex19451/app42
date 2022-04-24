FROM tomcat:9.0-jre8-alpine

WORKDIR /usr/local/tomcat/webapps/

RUN wget https://raw.githubusercontent.com/alex19451/app42/master/WebContent/Config.properties -P ROOT/

CMD ["catalina.sh", "run"]