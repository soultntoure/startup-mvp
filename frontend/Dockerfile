FROM node:14
WORKDIR /app
COPY ./frontend/package.json /
RUN npm install
COPY ./frontend/src /app/src
COPY ./frontend/public /app/public
RUN npm run build
CMD ["npm", "start"]
