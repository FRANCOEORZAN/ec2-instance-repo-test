# React/DjangoRF Authentication App

Authentication app using React and Django REST framework with session authentication.

## Installations

- backend

```
pip install djangorestframework
pip install django-cors-headers
```

- frontend

```
npm install axios
npm install react-bootstrap bootstrap
```

## Docker Credentials Restore

```
rm ~/.docker/config.json
docker login
```

## Docker redeploy

```
sudo docker system prune --all --volumes
sudo docker-compose up --build
```

## Connect to AWS DATABASE Tutorial

```
  https://django.how/resources/aws-rds-postgresql-instance-for-django-project/
```

## Install Github on EC2 Linux

```
sudo yum update
sudo yum install git
sudo yum install git
git version

```

## Install Docker and Docker-Compose on EC2 Linux

```
sudo yum update
sudo yum search docker
sudo yum info docker
sudo yum install docker
docker --version

sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
docker-compose version

https://www.cyberciti.biz/faq/how-to-install-docker-on-amazon-linux-2/
```

## Modifications

```
App. js --> change base url to the actual instance IP - no port :8000
```

## Git push

```
git init
git add .
git commit -m ""
git push -u origin main

git pull origin
```
