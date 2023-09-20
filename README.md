# What is Docker ?
The Docker open-source platform has revolutionized the way we create, deploy, and manage containerized applications




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
$ sudo docker container stop container-id

# How to add Docker in sudo group?
To create the docker group and add your user:

Create the docker group

$ sudo groupadd docker

Add your user to the docker group

$ sudo usermod -aG docker $USER

Log out and log back in so that your group membership is re-evaluated

Verify that you can run docker commands without sudo 

# What Is Docker Expose Port?
The expose keyword in a Dockerfile tells Docker that a container listens for traffic on the specified port

So, for a container running a web server, you might add this to your Dockerfile: 

EXPOSE 80

# Exposing Docker ports via EXPOSE or –expose
There are two ways of exposing ports in Docker:

Including an EXPOSE instruction in the Dockerfile
Using the -expose flag at runtime

EXPOSE Example:
----------------
EXPOSE 80

-expose Example:
----------------
docker run --expose=8080 test

docker run --expose=2000-3000 test

### -------------------------------------------------------------------------------------------------------------
# Azure Application Gateway
### --------------------------------------------------------------------------------------------------------------




