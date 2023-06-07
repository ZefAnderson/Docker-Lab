Lab 2

docker build -t lab:latest .
docker run -d --rm --name dlab -p 1234:1234 lab:latest
localhost:1234

Lab 3

//deploy stack
docker stack deploy -c docker-compose.yaml app-stack
//scale out first stack to 7 replicas
docker service scale app-stack_mywebsite1=7
//remove stack and delete containers
docker stack rm app-stack