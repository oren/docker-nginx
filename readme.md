# docker-nginx

# Setup

  docker build -t nginx .
  docker run --name nginx -d -p 3000:80 -v $(pwd):/usr/share/nginx/html nginx
  open http://localhost:3000
