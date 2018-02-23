FROM node:6.11.0

RUN npm install -g grunt-cli --silent

RUN git clone https://github.com/ChihChengLiang/eth-netstats

WORKDIR /eth-netstats

RUN npm install --silent

RUN grunt

CMD ["npm", "start"]