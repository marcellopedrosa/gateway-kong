# gateway-kong

1: create kong-net before
 
docker network create kong-net

2: start the database service to kong and konga

docker-compose up -d db 

3: up the other services

docker-compose up -d 
