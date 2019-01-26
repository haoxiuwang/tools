FROM debian:wheezy

RUN apt-get update -y && apt-get install --no-install-recommends -y -q curl python build-essential git ca-certificates
RUN mkdir /nodejs && curl https://nodejs.org/dist/v10.15.0/node-v10.15.0-linux-x64.tar.xz
RUN xz -d node-v10.15.0-linux-x64.tar.xz
RUN tar -xvf node-v10.15.0-linux-x64.tar
RUN mv node-v10.15.0-linux-x64 /nodejs 

ENV PATH $PATH:/nodejs/bin
