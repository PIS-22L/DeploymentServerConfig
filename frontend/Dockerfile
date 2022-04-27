FROM node:lts
WORKDIR /myApp
COPY ./build ./build
RUN npm install -g serve
CMD ["serve", "build"]