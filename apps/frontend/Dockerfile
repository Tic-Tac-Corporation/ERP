FROM node:20

WORKDIR /app

RUN npm install -g pnpm

COPY . .

RUN pnpm install

EXPOSE 5173

CMD ["pnpm", "dev", "--host", "0.0.0.0"]