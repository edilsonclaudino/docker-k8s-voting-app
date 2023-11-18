FROM node:10-slim

ADD https://github.com/krallin/tini/releases/download/v0.19.0/tini /tini
RUN chmod +x /tini

WORKDIR /app
COPY package*.json ./

RUN npm ci \
&& npm cache clean --force \
&& mv /app/node_modules /node_modules

COPY . .
ENV PORT 80
EXPOSE 80
ENTRYPOINT ["/tini", "--", "node", "server.js"]