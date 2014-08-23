FROM mesosphere/mesos:0.20.0
MAINTAINER Shingo Omura <everpeace@gmail.com>

RUN apt-get install curl
RUN locale-gen en_US.UTF-8
RUN dpkg-reconfigure locales

RUN curl -O http://downloads.mesosphere.io/marathon/marathon-0.6.1/marathon-0.6.1.tgz
RUN tar xzf marathon-0.6.1.tgz
