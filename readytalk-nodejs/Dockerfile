FROM debian:wheezy

RUN apt-get update -y && apt-get install --no-install-recommends -y -q curl python build-essential git ca-certificates
RUN curl https://nodejs.org/dist/v10.15.0/node-v10.15.0-linux-x64.tar.xz -o nodejs.tar.xz
RUN xz -d nodejs.tar.xz
RUN tar -xvf nodejs.tar -c /nodejs

ENV PATH $PATH:/nodejs/bin
