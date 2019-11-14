FROM httpd:2.4

COPY ./html/. /usr/local/apache2/htdocs/
COPY ./my-httpd.conf /usr/local/apache2/conf/

WORKDIR /usr/local/apache2/htdocs/
CMD ["apachectl", "-D", "FOREGROUND"]
EXPOSE 80

