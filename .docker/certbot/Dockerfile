#FROM ubuntu:latest
FROM certbot/certbot:latest

#EXPOSE 80 
 
 
#WORKDIR /certbot
#COPY . /certbot
#WORKDIR /certbot


#RUN apt-get update  

#RUN apt-get -y install certbot  

COPY 2.sh ./ 
 

ENTRYPOINT ["./certbot-entrypoint.sh"]
  

 
 
 

