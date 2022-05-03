FROM node:4-slim

RUN npm install express
RUN npm install redis@3

COPY files/ /files/
COPY test2.html/
CMD ["http-server", "/test2.html"]
EXPOSE 80
