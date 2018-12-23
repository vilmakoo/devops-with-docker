FROM ubuntu:16.04 

WORKDIR /app

RUN apt update && \
  apt-get install -y python python-dev python3-pip wget ffmpeg && \
  pip3 install pycrypto && \
  pip3 install --user --upgrade yle-dl
ENV LC_ALL=C.UTF-8 

ENTRYPOINT ["/root/.local/bin/yle-dl"]