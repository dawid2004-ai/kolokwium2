zad 1

docker pull httpd

docker run --name apache -d -p 8090:80 httpd

docker ps

docker logs apache

docker stop apache

docker rm apache

docker rmi httpd

zad 2 

docker build -t app .

docker run -p 5000 --name app -d app

