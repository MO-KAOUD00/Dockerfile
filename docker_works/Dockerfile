FROM ubuntu:20.04

RUN apt-get update && apt-get install -y nginx

RUN apt-get install -y curl

RUN rm -f /var/www/html/index.nginx-debian.html


RUN echo 'Welcome to DevOps World!' > /var/www/html/index.html


EXPOSE 8080


CMD ["nginx", "-g", "daemon off;"]

