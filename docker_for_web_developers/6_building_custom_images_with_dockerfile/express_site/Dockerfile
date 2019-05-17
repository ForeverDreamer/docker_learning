FROM node:latest

LABEL author="doerlee"

ENV NODE_ENV=production 
ENV PORT=3000

WORKDIR   /var/www
COPY      . .

RUN       npm install

EXPOSE $PORT

ENTRYPOINT ["npm", "start"]