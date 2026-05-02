FROM ubuntu:24.04

RUN apt-get update && apt-get install -y curl

RUN mkdir -p /app/data

WORKDIR /app

COPY greet .
COPY date .

CMD ["./date"]


