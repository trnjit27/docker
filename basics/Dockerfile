#Pull the latest ubuntu image from Docker-Hub
FROM ubuntu:latest

#Update and install the dependencies
RUN apt update -y

#Install nginx package
RUN apt install nginx -y

#Expose port 80 of the container
EXPOSE 80

#Start nginx service
CMD ["nginx", "-g", "daemon off;"]
