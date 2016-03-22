FROM tomgeorge/rpi-nginx
ENV AUTHOR=Docker
<<<<<<< HEAD

RUN mkdir -p /usr/share/nginx/html
COPY Hello_docker.html /usr/share/nginx/html

WORKDIR /usr/share/nginx/html
CMD cd /usr/share/nginx/html && sed -e s/Docker/$AUTHOR/ Hello_docker.html > index.html ; nginx -g 'daemon off;'
=======
COPY index.html /var/www/html/
>>>>>>> changed to use rpi images

