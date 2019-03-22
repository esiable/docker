FROM httpd:2
RUN apt update;
RUN apt upgrade;
COPY ./vhosts/test.conf /usr/local/apache2/conf/test.conf
RUN echo "Include /usr/local/apache2/conf/test.conf" \
    >> /usr/local/apache2/conf/httpd.conf
