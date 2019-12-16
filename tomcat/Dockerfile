
FROM tomcat

MAINTAINER DKA DEVELOP <6dafboy6@mail.ru>


#ENV TZ=Europe/Minsk
#RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone


RUN apt-get update && apt-get install -y default-jdk && rm -rf /var/lib/apt/list/*



EXPOSE 8080

