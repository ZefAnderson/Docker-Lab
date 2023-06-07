FROM node:latest
LABEL maintainer="Zef Anderson Docker Lab" 
LABEL description="in-class project using docker" 
LABEL cohort="16"
LABEL animal="tiger"
WORKDIR /usr/src/Lab
COPY . . 
EXPOSE 1234 2468 
RUN npm install
CMD ["node", "app.js"]

