FROM nginx:alpine
ENV http_proxy http://172.20.224.1:3128
ENV https_proxy http://172.20.224.1:3128
COPY dancook993/docker/index.html /usr/share/nginx/html
RUN export http_proxy=http://172.20.224.1:3128
RUN apk update
RUN apk add firefox-esr
