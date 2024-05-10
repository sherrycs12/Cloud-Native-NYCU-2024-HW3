FROM node:20-alpine
RUN mkdir /backend
WORKDIR /backend
COPY ./ /backend
EXPOSE 8888
RUN npm install
RUN npm run build
COPY .env.sample .env
CMD npm run dev