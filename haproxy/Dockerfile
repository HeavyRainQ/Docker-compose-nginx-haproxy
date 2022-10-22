FROM ubuntu:18.04

# install packages
RUN apt-get update \
  && apt-get install -y -qq haproxy

# add missing socket path
RUN mkdir /run/haproxy

CMD ["/usr/sbin/haproxy","-W","-db","-f","/etc/haproxy/haproxy.cfg"]
