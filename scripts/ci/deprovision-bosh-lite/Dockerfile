FROM ubuntu:trusty

RUN \
  apt-get update && \
  apt-get -y install \
    build-essential \
    python-pip

RUN \
  pip install awscli==1.6.6 && \
  pip install s3cmd
