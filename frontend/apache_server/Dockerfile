FROM httpd:2.4.51
COPY virtuelHost.apache.conf /usr/local/apache2/conf/virtuelHost.apache.conf

RUN echo "Include /usr/local/apache2/conf/virtuelHost.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf
