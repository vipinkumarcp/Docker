#base image

FROM node:14-alpine


WORKDIR /usr/app 


COPY ./packa* ./
#install dependemcies


RUN npm install 
COPY ./ ./



CMD [ "npm","start" ]
