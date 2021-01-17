FROM ubuntu:20.10

RUN apt-get update && \
    apt-get -yqq install \
    g++ cmake libboost-all-dev libpcap-dev

COPY ./* /source/

# User root
RUN bash -c "cd /source/install && bash /source/install"
