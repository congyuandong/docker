FROM daocloud.io/library/node:6.11.3-slim

MAINTAINER congyuandong <congyuandong@gmail.com>

COPY ./sources.list /etc/apt/sources.list

RUN apt-get update \
	&& apt-get install -y python make gcc g++ \
	&& apt-get install -y nginx

RUN npm install -g cnpm --registry=https://registry.npm.taobao.org

EXPOSE 80
