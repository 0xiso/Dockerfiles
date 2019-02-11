FROM debian:stretch-slim

RUN set -ex \
 && apt-get update \
 && apt-get dist-upgrade \
 && apt-get install -y --no-install-recommends suricata \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*