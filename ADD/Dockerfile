FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD  https://kapeli.com/cheat_sheets/Dockerfile.docset/Contents/Resources/Documents/index /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]