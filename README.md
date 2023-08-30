# Azure Docker Notes Deep Dive
Installation Docker on Azure VM NAME="Ubuntu" and VERSION="20.04.6 LTS (Focal Fossa)"

$ sudo apt update

$ sudo apt install docker.io -y

# How to start docker ?
$ sudo service docker start

# How to check docker status?
$ sudo service docker status

# How to check docker images?
$ sudo docker image ls

$ sudo docker images

# How to check docker container?
$ sudo docker container ls

$ sudo docker ps

# How to stop container ?
$ sudo docker container stop <container-id>

# How to add Docker in sudo group?
To create the docker group and add your user:

Create the docker group

$ sudo groupadd docker

Add your user to the docker group

$ sudo usermod -aG docker $USER

Log out and log back in so that your group membership is re-evaluated

Verify that you can run docker commands without sudo 



