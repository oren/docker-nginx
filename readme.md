# docker-nginx

Website served by Nginx inside Docker container

![demo](demo.gif)

## Setup

    docker build -t nginx .
    docker run --name nginx -d -p 3000:80 -v $(pwd)/website:/usr/share/nginx/html nginx
    open http://localhost:3000
