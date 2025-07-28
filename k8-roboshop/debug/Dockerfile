# FROM almalinux:9
# RUN dnf install telnet net-tools iputils -y
# RUN useradd roboshop
# USER roboshop
# CMD ["sleep","100000"]

FROM node:alpine3.21
RUN npm install
RUN useradd roboshop
USER roboshop