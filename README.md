# SP-Redis
Sample Repository to use redis

## How To
Just build containers by `docker-compose up` then, access redis via client.

```
$ docker-compose up

$ ./connect-via-client.sh

redis:6379>
```

Or you could connect redis directly from your local machine if you've already installed redis-client

```
# (optional)
$ brew install redis

$ redis-cli

127.0.0.1:6379>
```
