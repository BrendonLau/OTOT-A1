# pull official base image
FROM node:13.12.0-alpine

COPY . .

# install app dependencies
RUN npm install --quiet

ENV PORT=8080
EXPOSE 8080

# the command that starts our app
CMD ["npm", "start"]