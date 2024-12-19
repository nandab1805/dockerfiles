FROM almalinux:8
RUN  yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY  https://raw.githubusercontent.com/daws-76s/dockerfiles/refs/heads/main/LABEL/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]