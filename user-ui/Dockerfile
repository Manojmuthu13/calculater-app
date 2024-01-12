FROM node:18.17.0
WORKDIR /opt
COPY package*.json ./
RUN npm install
RUN npm install -g npm
COPY . .
#RUN npm run build
EXPOSE 3000
CMD ["npm", "start", "index.js"]
