FROM node:10

# app dir
WORKDIR /usr/src/app
#coppy package bỏ vào WORKDIR
COPY package*.json ./
#run để tải về các thư viện cho dự án
RUN npm install

#coppy toan bo code bỏ vào WORKDIR
COPY . .

#sử dụng port này trên docker
EXPOSE 8080

CMD ["node", "index.js"]