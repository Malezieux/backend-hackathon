FROM node
RUN mkdir /backend-main
COPY . /backend-main
CMD cd /backend-main && npm install && npm start
ENV CONNECTION_STRING=mongodb+srv://philippemalezieux:Nhr1wWAd1IAjGyIF@cluster0.2ln8yof.mongodb.net/
EXPOSE 3000