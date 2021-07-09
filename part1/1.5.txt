docker run -d -it --name secret_alpine devopsdockeruh/simple-web-service:alpine
docker images
docker exec -it secret_alpine sh
tail -f ./text.log
