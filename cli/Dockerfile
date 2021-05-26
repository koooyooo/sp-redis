FROM alpine:3.12

RUN apk update && apk add redis

WORKDIR /

COPY run.sh .

# CMD ["/usr/bin/redis-cli", "-h", "redis"]
