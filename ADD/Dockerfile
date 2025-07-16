FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/skype755/Docker-Concept/refs/heads/main/FROM/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]