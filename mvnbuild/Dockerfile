FROM maven:3.5.2-jdk-8-alpine

RUN apk update && \
    apk add git

WORKDIR /tmp/project

RUN git clone https://github.com/alex19451/app42.git ./

CMD mvn package