### Redis, Docker, Ngix mix

> https://developer.redis.com/create/docker/nodejs-nginx-redis/

### Deploy the application
$ docker-compose up -d

### Test the application
http://localhost  [comment]: <> (since the port is simply 80 https://localhost runs without any port included)


### Monitoring Redis Keys
> $ redis-cli
> 127.0.0.1:6379> monitor
> OK
Everytime the application is hit redis monitoring is enabled
