FROM node:20-alpine
RUN mkdir /frontend
WORKDIR /frontend
COPY ./ /frontend
EXPOSE 5173
RUN npm install
CMD npm run dev