FROM node:16.3.0-alpine

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN sed -i 's/\*\*\* CENSORED \*\*\*/CTF{Th1s_Is_y0oo00o0o000our_fl4g!}/' app.js
EXPOSE 3000
CMD ["node", "app.js"]