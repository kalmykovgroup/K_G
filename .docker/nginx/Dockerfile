FROM nginx


 
COPY ./docker-entrypoint.sh /nginx 

ENTRYPOINT ["sh", "docker-entrypoint.sh"] 

EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]
   