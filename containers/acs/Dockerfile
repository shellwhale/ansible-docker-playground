FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install -y software-properties-common
RUN apt-add-repository --yes --update ppa:ansible/ansible
RUN apt-get install -y ansible iputils-ping

ENTRYPOINT [ "/bin/bash" ]