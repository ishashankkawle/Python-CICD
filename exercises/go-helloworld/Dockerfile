FROM golang:alpine
WORKDIR /app
ADD . .
RUN go build -o helloworld
EXPOSE 6111
CMD ["./helloworld"]