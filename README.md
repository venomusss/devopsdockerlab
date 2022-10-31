### Node app runs at 80 port

## Build image

docker build . -t volodymyrmushii/lab1:latest

## Run container

docker run -p 80:80 -d --memory="50m" --cpus=2 volodymyrmushii/lab1:latest
