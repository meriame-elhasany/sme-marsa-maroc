FROM node:20-alpine
WORKDIR /app
COPY server/package.json ./
RUN npm install --production || true
COPY server ./server
EXPOSE 4000
CMD ["node", "server/index.js"]
