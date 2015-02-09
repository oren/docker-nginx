# docker-nginx

## Setup

    docker build -t nginx .
    docker run --name nginx -d -p 3000:80 -v $(pwd)/website:/usr/share/nginx/html nginx
    open http://localhost:3000

## alternative

docker run --name some-nginx -v /some/content:/usr/share/nginx/html:ro -d nginx
https://registry.hub.docker.com/u/jwilder/nginx-proxy
