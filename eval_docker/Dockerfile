FROM nginx:latest
COPY ./startbootstrap-freelancer-gh-pages/ /usr/share/nginx/html/

EXPOSE 8080

ENV NAME="Mathias"

# install ping
RUN apt-get update && apt-get install -y iputils-ping

CMD ["nginx", "-g", "daemon off;"]