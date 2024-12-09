FROM nginx:stable-alpine3.20-perl
RUN rm -rf /usr/share/nginx/html/*
COPY code /usr/share/nginx/html
COPY expense.conf /etc/nginx/conf.d/expense.conf
COPY expense.conf /etc/nginx/default.d/expense.conf
COPY nginx.conf /etc/nginx/nginx.conf
USER nginx
