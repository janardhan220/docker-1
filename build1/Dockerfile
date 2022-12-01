FROM nginx
RUN apt update
RUN apt install git elinks -y
RUN rm -f /usr/share/nginx/html/*
COPY html/ /usr/share/nginx/html/
#change nginx to run on new port used in EXPOSE
#RUN git clone https://github.com/abdulshajahan/nginxpro1.git /usr/share/nginx/html/
#RUN echo "Welcome to nginx check echo working!!!!" > /usr/share/nginx/html/index.html
#ENTRYPOINT ./docker-entrypoint.sh
#EXPOSE 8888