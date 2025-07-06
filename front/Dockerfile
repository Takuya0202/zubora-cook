FROM node:22
WORKDIR /app
COPY ./react-app/package*.json ./
WORKDIR /app/react-app
RUN npm install
COPY ./react-app .
EXPOSE 5173
CMD ["npm" , "run" , "dev"]