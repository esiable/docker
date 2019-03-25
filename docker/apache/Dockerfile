FROM httpd:2
RUN apt-get update
RUN apt-get upgrade
COPY ./vhosts/* /usr/local/apache2/conf/vhosts/
RUN echo "Include /usr/local/apache2/conf/vhosts/*" \
    >> /usr/local/apache2/conf/httpd.conf


