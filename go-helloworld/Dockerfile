# Setting the base image
FROM golang:alpine
LABEL maintainer = "Oyindamola Victor"

COPY . /go/src/app
WORKDIR /go/src/app

RUN go build -o helloworld
EXPOSE 6111

CMD ["./helloworld"]