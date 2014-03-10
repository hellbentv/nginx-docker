nginx-docker
============

docker build -t nginx_img_1 .

docker run -a stdout -rm --name=descriptivename -v /srv/localhtml:/usr/share/nginx/html -p 80:80 -i -t nginx_img_1



   
