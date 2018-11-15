FROM ubuntu:16.04
RUN useradd drop-core
RUN apt-get update && apt-get -y install rrdtool python
COPY ./rrd /home/drop-core/
