FROM nginx:1.17.0-alpine

COPY ./assets/nginx/ssl  /etc/nginx/ssl
COPY ./assets/nginx/nginx.conf  /etc/nginx/nginx.conf
COPY ./assets/nginx/conf.d/  /etc/nginx/conf.d/

VOLUME /var/log/nginx/default
VOLUME /var/log/nginx/ruby
