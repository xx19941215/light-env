FROM ubuntu:16.04
MAINTAINER "contact@xiaoxiao.work"

COPY sources.list /etc/apt/sources.list

RUN set -ex \
&& apt-get update \
&& apt-get upgrade --no-install-recommends --no-install-suggests -y \
&& rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]