FROM openjdk:24-slim-bullseye

RUN apt-get update --fix-missing
RUN apt-get install -y vim
COPY ./ /var/www
WORKDIR /var/www
EXPOSE 8080
