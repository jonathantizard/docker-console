FROM phusion/baseimage
MAINTAINER Jonathan Tizard

ENV TERM xterm

RUN apt-get update \
 && apt-get install -y git \
 && apt-get install -y zsh \
 && apt-get install -y wget

RUN wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | bash
RUN chsh -s `which zsh`

WORKDIR /root
