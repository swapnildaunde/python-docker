docker build . -t pythondemo:latest
docker images
docker run --name test-python -d img_id
docker exec -it container_id /bin/bash 
docker logs container_id
