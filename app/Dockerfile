FROM golang:1.22.2

RUN go install github.com/cosmtrek/air@latest
RUN go install github.com/k1LoW/runn/cmd/runn@latest

WORKDIR /app

CMD ["air"]

EXPOSE 80
