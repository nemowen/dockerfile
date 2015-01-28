# This dockerfile users the centos image
# VERSION 1 - EDITION 1
# Author: nemowen

FROM		centos:6.5
MAINTAINER	nemowen
# RUN yum install -y redis
ADD redis-2.8.19.tar.gz /usr/local/
ENTRYPOINT ["/usr/local/redis-2.8.19/src/redis-server" "/usr/local/redis-2.8.19/redis.conf"]
EXPOSE 6379