FROM acrisliu/jenkins-nodejs:lts
ENV http_proxy http://172.20.224.1:3128
ENV https_proxy http://172.20.224.1:3128
USER root
RUN apk add --update docker openrc
RUN rc-update add docker boot
RUN apk update 
RUN apk add firefox-esr
RUN export http_proxy="http://172.20.224.1:3128"
