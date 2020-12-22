FROM node:alpine

ENV PORT=3000

RUN apk add --no-cache automake gcc make g++ zlib-dev

WORKDIR /usr/share/app

EXPOSE $PORT

CMD ["npm", "start"]
