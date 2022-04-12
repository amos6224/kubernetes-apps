FROM node
LABEL app = 'my second app'

WORKDIR gilbert-node
COPY package.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]