FROM node:18-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

# ENV MONGO_USER=nikhilagrawxl
# ENV MONGO_PASS=nikhilagrawxl
# ENV MONGO_DATABSE=todonikhil
# ENV PORT=5000
# ENV NODE_ENV='production'

EXPOSE 5000

CMD ["npm", "start"]