##Docker commands

Use a base image to run a container that we can interact with (-i):

`docker run -t -i gunnie/example /bin/bash`

Run a detached (-d) container that exposes port 3000:

`docker run -p 80:3000 -d gunnie/example`

Build an image based on Docker file in current directory:

`docker build . -t gunnie/example`

List all containers:

`docker ps -a`

List all images:

`docker images`

To remove a container:

`docker rm <CONTAINER ID>`

To remove images:

`docker rmi <IMAGE ID>`

Logging by streaming the output from the running container’s STDOUT and STDERR:

`docker logs --follow`
