FROM golang:1.23.3-alpine3.20

RUN apk update  
RUN apk upgrade  
RUN apk add --no-cache git
RUN apk add --no-cache bash

RUN go install github.com/air-verse/air@latest