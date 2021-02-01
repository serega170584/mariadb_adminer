FROM node:15
EXPOSE 4200
RUN npm install -g @angular/cli
RUN git clone https://github.com/serega170584/shop-backend.git
WORKDIR shop-backend
RUN npm install
RUN ng serve --open