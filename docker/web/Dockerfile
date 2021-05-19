FROM golang:1.16.4-alpine
RUN apk update && apk add git

RUN GO111MODULE=off
RUN go get -u github.com/cosmtrek/air
ENV GO111MODULE="on"

RUN mkdir /go/src/gin-jwt-template
WORKDIR /go/src/gin-jwt-template
ADD . /go/src/gin-jwt-template
