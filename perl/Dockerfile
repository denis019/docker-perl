FROM phusion/baseimage:latest

RUN DEBIAN_FRONTEND=noninteractive

RUN echo 'DPkg::options { "--force-confdef"; };' >> /etc/apt/apt.conf

RUN apt-get update -y && \
    apt-get upgrade -y

RUN apt-get install -y build-essential

RUN cpan Devel::Camelcadedb

RUN mkdir /src

WORKDIR /src