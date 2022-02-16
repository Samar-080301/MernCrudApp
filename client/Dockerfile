FROM node:13-alpine
EXPOSE 3000
RUN mkdir /app
RUN mkdir -p /home/app
COPY . /home/app
WORKDIR /home/app
RUN npm install
CMD ["npm","run","start"]
