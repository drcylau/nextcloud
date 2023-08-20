FROM nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf
RUN mkdir -p /var/www/data
RUN chown www-data:www-data /var/www/data 
RUN	chmod 0770 /var/www/data