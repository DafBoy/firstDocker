
FROM ubuntu:trusty 

MAINTAINER DKA DEVELOP <6dafboy6@mail.ru>


ENV TZ=Europe/Minsk
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone


RUN apt-get update && apt-get install -y apache2 && apt-get install -y ntp && apt-get install -y default-jdk && rm -rf /var/lib/apt/list/*


WORKDIR /var/www/site
EXPOSE 3000
CMD apachectl -D FOREGROUND

