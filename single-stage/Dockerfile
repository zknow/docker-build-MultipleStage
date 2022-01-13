FROM golang:1.17.6-alpine

WORKDIR /app

ADD . /app

RUN cd /app && go build -o app

EXPOSE 8080

ENTRYPOINT ./app