FROM nginx:stable-alpine

RUN apk add bash

COPY ./infra/web/default.conf /etc/nginx/conf.d/default.conf
COPY ./api /var/www