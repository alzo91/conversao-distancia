# conversao-distancia

### Url DockerHub

https://hub.docker.com/repository/docker/zotarelli/conversao-distancia/tags

# commands

### build image

docker build . -t zotarelli/conversao-distancia:v3

### rename or creating tag

docker tag zotarelli/conversao-distancia:v3 zotarelli/conversao-distancia:latest

### running local

docker run -d --name cdistancia2 -p 5010:5000 zotarelli/conversao-distancia:latest
``You can access by http://localhost:5010`

### publish or push your image

docker push zotarelli/conversao-distancia:latest

###
