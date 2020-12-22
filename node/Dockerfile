FROM node:alpine

ENV PORT=3000

RUN apk add --no-cache automake autoconf gcc make g++ zlib-dev python

WORKDIR /usr/share/app

EXPOSE $PORT

CMD ["npm", "start"]
