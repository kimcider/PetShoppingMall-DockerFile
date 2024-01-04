FROM httpd
ENV VIRTUAL_HOST=www.petmeetsworld.com
ADD httpd.conf /usr/local/apache2/conf
ADD httpd-vhosts.conf /usr/local/apache2/conf/extra
WORKDIR /usr/local/apache2
EXPOSE 80