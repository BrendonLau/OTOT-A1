# pull official base image
FROM node:13.12.0-alpine

COPY . .

# install app dependencies
RUN npm install --quiet


# the command that starts our app
CMD ["node", "index.js"]