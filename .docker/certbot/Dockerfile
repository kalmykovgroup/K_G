FROM ubuntu:latest
#FROM certbot/certbot:latest

#EXPOSE 80 
 
 
#WORKDIR /certbot
#COPY . /certbot
#WORKDIR /certbot


RUN apt-get update 
#RUN apt-get -y upgrade 

#RUN apt-get -y install certbot 

RUN apt-get -y install dos2unix

COPY 2.sh ./ 


RUN dos2unix -n ./2.sh ./3.sh

ENTRYPOINT ["./3.sh"]
  

 
 
 

