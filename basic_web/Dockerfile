# Version: 0.0.1
FROM ubuntu:16.04
MAINTAINER Tom Monte "tmonte@gmail.com"
LABEL version =" 1.0" location =" Pennsylvania" type =" Data Center" role =" Web Server" 
RUN apt-get update; apt-get install -y nginx
RUN echo 'Hi, I am in your container' \
>/var/www/html/index.html
EXPOSE 80
