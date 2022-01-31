FROM linuxserver/nginx
LABEL maintainer=brandontylergibbs@gmail.com

ENV arch='x86_64'

COPY ./conf/ /
COPY . /site

EXPOSE 80 443

VOLUME ["/config"]
