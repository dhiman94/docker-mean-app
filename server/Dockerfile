FROM node:13

WORKDIR /usr/src/app

# copy package.json and package-lock.json to working dir
COPY package*.json ./ 

# install packages
RUN npm install

COPY . ./

EXPOSE 8080

CMD ["npm", "start"]

