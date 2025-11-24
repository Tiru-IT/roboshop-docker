FROM node:20
WORKDIR mkdir /opt/server
COPY package.json
COPY *.js 
RUN npm install
ENV MONGO="ture" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"

CMD ["node", "server.js"]