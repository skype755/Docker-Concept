FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/skype755/Docker-Concept/refs/heads/main/FROM/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html # when we add from internt there is no permissions so we need to give the give permissions as instructions
CMD ["nginx", "-g", "daemon off;"]