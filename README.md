# Docker---Tutor---Edit---Copy

To list Docker containter
```bash
Docker ps
```

To list Docker images 
```
docker images
````

To edit/view Docker containter
```bash
docker exec -it tutor_local_lms_1 bash
````

To edit/view Docker Images
````bash
docker run --rm -it image.name bash
````

To copy file/folder from Docker container to current dir
```bash
 docker cp tutor_local_lms_1:openedx/themes/edx-custom-theme  .
 ```
 
 To Copy file/folder to Docker container from current dir 
 ```bash 
  docker cp filenae tutor_local_lms_1:openedx/edx-platform/ 
 ````
 
 


