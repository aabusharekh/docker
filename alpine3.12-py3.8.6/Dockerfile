FROM alpine:3.14
RUN apk update && apk upgrade
RUN apk add --no-cache python3 
RUN rm -rf \
      /usr/share/man/* \
      /usr/includes/* \
      /var/cache/apk/* 
ENTRYPOINT ["sh"]
