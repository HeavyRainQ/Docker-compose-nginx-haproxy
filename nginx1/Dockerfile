ARG VERSION=latest

FROM nginx:$VERSION

RUN apt-get update

COPY ./index.html /usr/share/nginx/html/
