## To list out all images 
Docker images

## To pull images from registry 
Docker pull imageName
    If we do not mention the image verion (**tag**) it will intsalll the latest .

No need to login if the image is available in public .


## Docker info 
    provides information on where Docker details are stored .

## docker -v
## docker version confirms successfull installation of Docker.
 container without name 

General Docker root dir is /var/lib/Docker this is where dfata is stored.
in mac it uses hyperkit.we have to log in to hyoerkit to see these details.


To create a container We need a parent process.



To run a container
Docker run alpine:tag
Docker run node //without tag is for to latest version 
creates a
Docker run -d --nsmae alpine:tag imagename:imahgetag


Docker logs containername //
Docker logs -f container name  to see in forground // 


docker stop container anme/ID
which stops the container and parent process

Docker start 

Docker kill



to list id 
Docker ps -q
docker rm $(docker ps -q)

docker rm $(docker ps -aq)



To execute a child process 
docker exec containername command
-i interactive
-t terminal

docker run alpine date




From os
mainitaner
copy 



Docker inspect name of image
