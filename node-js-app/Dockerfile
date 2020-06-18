FROM alpine
LABEL maintainer="kamallatif@hotmail.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Kamal Latif"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
