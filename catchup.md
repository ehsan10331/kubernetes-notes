### Download the image and test 
```
docker image ls
docker container ls -a
docker pull kammana/nodeapp:v1
docker run -itd -p 80:8080 --name mycontainer <image id>
docker container ls
### test: Access the application
```
