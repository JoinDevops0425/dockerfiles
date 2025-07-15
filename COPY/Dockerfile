FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/
COPY index.html /user/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]