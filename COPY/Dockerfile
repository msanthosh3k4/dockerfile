FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off;"]
COPY index.html /usr/share/nginx/index.html