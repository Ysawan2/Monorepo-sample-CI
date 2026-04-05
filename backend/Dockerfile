FROM golang:1.20

WORKDIR /app

COPY main.go main.go

RUN go build main.go

CMD ["go", "run", "main.go"     ]