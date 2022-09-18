FROM node:12
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied where available (npm@5+)
COPY package*.json ./
<<<<<<< HEAD
RUN npm install .
=======
RUN npm install . 
>>>>>>> 8aa1a602ffa7b6715592fa00e282c7891b2f8517
# Bundle app source
COPY . .
EXPOSE 8080
CMD [ "npm", "run", "prod" ]
