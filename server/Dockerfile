#backend base image
FROM node:22

#set the working directory
WORKDIR /app

#copy the package files
COPY package*.json ./

#install the dependancies
RUN npm install

#copy everything else
COPY . . 

#expose the backend port
EXPOSE 4051

#run the application
CMD ["npm", "start"]