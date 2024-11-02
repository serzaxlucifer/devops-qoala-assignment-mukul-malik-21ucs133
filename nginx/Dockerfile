FROM nginx:latest
# Changed latests to latest (syntax fixing)

COPY nginx.conf /etc/nginx/nginx.conf
# Typo nginix to nginx

COPY ./html /usr/share/nginx/html
#Typo html fixed.

EXPOSE 80
# Transformed to integral value

CMD ["nginx", "-g", "daemon off;"]
#of; fixed to off;!
