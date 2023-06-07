docker build -t lab:latest .
docker run -d --rm --name dlab -p 1234:1234 lab:latest
localhost:1234