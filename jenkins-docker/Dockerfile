
FROM ubuntu 
RUN apt-get update -y \
 && apt-get upgrade -y \
 && apt-get install git -y \
 && apt-get install apache2 -y \
 && echo "Hello World!!" > /var/www/html/index.html
EXPOSE 80
