FROM node:alpine

RUN mkdir -p /app
ENV PORT 3000

WORKDIR /app

COPY package.json package-lock.json /app/

RUN yarn install --production

COPY . /app

RUN yarn build

EXPOSE 2000

CMD ["yarn", "dev", "--port", "2000"]
