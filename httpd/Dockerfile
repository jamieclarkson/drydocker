# 'Dockerfile'.

# Dockerize httpd 

# To build:
# host$ sudo docker build -t httpd/httpd:2.4 .

# To run:
# host$ sudo docker run -t -i -p 80:80 httpd/httpd:2.4

# Docker Official Repo Apache Build

FROM httpd:2.4

MAINTAINER Jamie Clarkson

COPY ./public_html/ /usr/local/apache2/htdocs/

EXPOSE 80



