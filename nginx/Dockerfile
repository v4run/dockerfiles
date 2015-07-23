############################################################
# Dockerfile to build nginx container images
# Based on Ubuntu
############################################################

FROM v4run/ubuntu:14.04.2

MAINTAINER Varun Vasan V

RUN apt-get update

# Installing Supervisor daemon
RUN apt-get update && apt-get install -y nginx
ADD supervisord.conf /etc/supervisor/conf.d/nginx.conf
EXPOSE 80