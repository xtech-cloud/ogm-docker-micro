# **************************************
#
# OpenGM Micro
#
# VERSION: v2.9.3.a
#
# *************************************

FROM alpine:3.12

MAINTAINER XTech Cloud "xtech.cloud"

ENV container docker
ENV MICRO_REGISTRY consul

ADD micro /usr/local/bin/
RUN chmod +x /usr/local/bin/micro

ENTRYPOINT ["micro"]

