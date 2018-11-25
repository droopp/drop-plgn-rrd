FROM ubuntu:16.04
RUN useradd drop-core
RUN apt-get update && apt-get -y install rrdtool python python-pip librrd-dev
RUN pip install rrdtool
COPY ./rrd /home/drop-core/
