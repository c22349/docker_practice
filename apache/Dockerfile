FROM ubuntu:21.10

RUN apt update \
&& apt install -y apache2

CMD ["apachectl", "-D", "FOREGROUND"]
