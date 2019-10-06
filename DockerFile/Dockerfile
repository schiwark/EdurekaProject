FROM devopsedu/webapp

MAINTAINER Sushant Chwarkar

LABEL version="1.0"
LABEL description="First image with Dockerfile."

RUN apt-get update
RUN apt-get install apache2
RUN service apache2 start

COPY index.php /projCert/website
COPY functions.php /projCert/website
COPY config.php /projCert/website


EXPOSE 80
