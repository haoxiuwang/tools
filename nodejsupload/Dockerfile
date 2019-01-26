FROM whx/nodejs:readytalk

RUN mkdir /app

RUN git clone https://github.com/whxcctv/fileupload-nodejs.git /app
WORKDIR /app
ENV PATH $PATH:/nodejs/bin
RUN npm install
CMD ["node","app.js"]


