FROM alpine:3.23

RUN apk add --no-cache bash curl postgresql-client && \
  curl -L -o /usr/bin/dbmate 'https://github.com/amacneil/dbmate/releases/download/v2.30.0/dbmate-linux-amd64' && \
  chmod +x /usr/bin/dbmate

ENTRYPOINT ["dbmate"]
