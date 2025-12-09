FROM nginx:alpine

RUN sed -i 's/listen       80;/listen       6000;/' /etc/nginx/conf.d/default.conf

RUN rm -rf /usr/share/nginx/html/*

COPY . /usr/share/nginx/html/

EXPOSE 6000
