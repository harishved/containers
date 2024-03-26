# containers
Some container definition files on storm

Build the containers using # apptainer build --fakeroot <container_name>.sif <definition file>.def
Then  you can enter a shell prompt inside the container using $ apptainer shell -B <path> <container_name>.sif
or excecute a command inside the container with $ apptainer exec -B <path> <container_name>.sif <command>
where <path> is the directory tree path that you want available inside the container (example /mnt/md0) and <command> is the command you want to run inside the container.



