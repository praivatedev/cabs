#base image
FROM node:22

#working directory in the container
WORKDIR /app

#copy the package files
COPY package*.json ./

#install the dependancies
RUN npm install

#copy everything else
COPY . . 

#expose frontend port
EXPOSE 5173

#start the frontend
CMD ["npm", "run", "dev"]