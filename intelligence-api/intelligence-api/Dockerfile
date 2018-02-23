FROM node:6.11.0

RUN git clone https://github.com/ChihChengLiang/eth-net-intelligence-api &&\
    cd eth-net-intelligence-api &&\
    npm install --silent

WORKDIR /eth-net-intelligence-api

CMD ["node", "app.js"]