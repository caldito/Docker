#Use an existing image as a base
FROM alpine

#Download and install dependencies
RUN apk add --update redis

#What to do what to do when starts as a container
cmd ["redis-server"]