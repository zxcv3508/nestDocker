FROM alpine

RUN apk add git && git clone https://github.com/zxcv3508/nestAPI.git && apk add --update nodejs npm

WORKDIR /nestAPI/

#RUN npm install --only=production
RUN npm i
RUN npm run build

CMD ["node", "dist/main.js"]

