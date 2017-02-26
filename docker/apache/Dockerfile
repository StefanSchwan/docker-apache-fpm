FROM httpd:alpine
RUN apk add --update\
          bash \
          tree \
          vim
COPY ./conf/httpd.conf /usr/local/apache2/conf/httpd.conf
COPY ./conf/httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf
