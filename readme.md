Learning how docker is used in production

'docker images' - list all docker images in our repository
'docker-compose up' - looks in the docker-compose.yml file and attempts to spin up containers found in there
* more specifically, docker-compose does the following:
** creates a container
** attaches
** runs the program (prints out log of what it did)

Note: Docker containers only run as long as the command is active, so once the program
is finished running, the container will stop.

'docker ps' - list active processes
* -a for listing all containers (not just active)

To remove images, run 'docker rm {Image-ID}'
