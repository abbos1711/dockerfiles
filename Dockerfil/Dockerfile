#bu mening docker file'im

FROM debian:buster-slim

RUN apt-get update

RUN apt-get install -y nginx

COPY ./index1.html /var/www/html

CMD nginx -g 'daemon off;' 