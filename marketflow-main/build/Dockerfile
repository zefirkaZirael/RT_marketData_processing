FROM golang:1.23

WORKDIR /app

COPY . .

RUN go build -o marketflow ./cmd

EXPOSE 8080

CMD ["./marketflow"]
