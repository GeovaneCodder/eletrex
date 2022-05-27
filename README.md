## Para rodar o servidor local
#### Nescessário ter o Docker
docker run -i -t -v $PWD:/usr/share/nginx/html --name nginx-mainline -p 8080:80 nginx:mainline-alpine