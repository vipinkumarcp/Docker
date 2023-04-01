#Use an existing docker image base

FROM alpine


#download and install dependency

RUN apk add --update redis



#tell the image what to do when its start as a container


CMD ["redis-server"]
