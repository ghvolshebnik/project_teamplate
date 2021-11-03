FROM alpine
RUN apk add --no-cache bash curl wget busybox-extras netcat-openbsd python3 postgresql-client --update py3-pip && \
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
