FROM nginx:alpine

RUN rm -rf /etc/nginx/conf.d/*.conf
COPY list.conf /etc/nginx/conf.d/
RUN chown -R nginx:nginx /etc/nginx/conf.d/

CMD ["nginx", "-g", "daemon off;"]
