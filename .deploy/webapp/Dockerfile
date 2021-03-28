FROM nginx:alpine

WORKDIR /usr/share/nginx/html
COPY package.json docs ./
COPY .deploy/webapp/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80
