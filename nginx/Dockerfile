FROM nginx

COPY ./nginx.conf /etc/nginx/nginx.conf

COPY ./favicon.ico /var/www/html/favicon.ico

CMD ["nginx", "-g", "daemon off;"]