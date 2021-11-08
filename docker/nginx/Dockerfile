FROM nginx

ADD ./docker/nginx/site.conf /etc/nginx/conf.d/default.conf

RUN mkdir -p /var/www/public
ADD ./public/ /var/www/public/
