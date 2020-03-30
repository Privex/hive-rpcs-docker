FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
ADD nginx.conf /etc/nginx/nginx.conf
ADD sites-enabled/ /etc/nginx/conf.d
