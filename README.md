```
# Build a docker image (node) based on a dockerfile (node_dockerfile)
docker build -f node_dockerfile -t node
# Check the docker images
docker images
# Run the docker image (node) and do some checks 
docker run -it node:latest /bin/sh
```
