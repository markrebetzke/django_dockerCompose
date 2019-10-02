# django_dockerCompose

https://docs.docker.com/compose/django/
sudo mkdir /mnt/django
chown ubuntu:ubuntu /mnt/django
sudo docker-compose run web django-admin startproject mysite .
Make change to database file
sudo docker-compose up -d
