FROM alpine:3.18.4
RUN apk update && apk upgrade
RUN rm -rf \
      /usr/share/man/* \
      /usr/includes/* \
      /var/cache/apk/* 
ENTRYPOINT ["sh"]
