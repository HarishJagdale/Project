FROM devopsedu/webapp 
RUN rm -rf /var/www/html/*
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf
ADD . /var/www/html
CMD apachectl -D FOREGROUND
