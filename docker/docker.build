FROM ubuntu:16.04
RUN apk add --no-cache curl wget busybox-extras net-cat-openbsd py-pip \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
