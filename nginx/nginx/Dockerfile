FROM nginx:1.21

RUN rm /etc/nginx/conf.d/default.conf

COPY ./nginx/nginx/default.conf /etc/nginx/conf.d/default.conf

COPY ./nginx/nginx/ssl.conf /etc/nginx/conf.d/ssl.conf