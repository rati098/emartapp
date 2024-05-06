# Stage 1: Build Angular application
FROM node:14 AS build

WORKDIR /app
COPY . .
RUN npm install --yes
CMD ["npm", "start"]
