FROM node:20
EXPOSE 8080
ENV DB_HOST="mysql"
RUN mkdir /app 
WORKDIR /app 
COPY *.js .
COPY *.json .
RUN  npm install
CMD [node","index.js"]