FROM node:20

WORKDIR /app

RUN npm install -g pnpm

COPY . .

RUN pnpm install

EXPOSE 3000

CMD ["pnpm", "start:dev"]