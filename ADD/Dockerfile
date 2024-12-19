FROM almalinux:8
RUN  yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD  https://raw.githubusercontent.com/daws-76s/notes/refs/heads/master/finalsession.txt /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]