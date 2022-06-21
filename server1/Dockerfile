FROM ubuntu
RUN apt-get update
RUN apt install apache2
COPY index.html /var/www/html/
EXPOSE 80
RUN echo "SERVERNAME 127.0.0.1" >> /etc/apache2/apache2.conf
