FROM nginx:latest

RUN apt-get update
RUN apt-get install git -y

COPY ./default.conf /etc/nginx/conf.d/default.conf
EXPOSE 80

ENTRYPOINT ["nginx","-g","daemon off;"]
