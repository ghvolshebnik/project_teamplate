FROM alpine
RUN apk add --no-cache bash curl wget busybox-extras netcat-openbsd python3 --update py3-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
