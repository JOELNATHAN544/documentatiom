# DOCKER

## What's docker ?

#### An open-source platform used by developers to help them automate the deployment of apps inside containers.

#### **Containerisation:** Allows developers to bundle a single, portable package called a container. Containerising tool used to create containers.

## Commands to install docker ..

#### Here are some commands to install docker

1. sudo apt update

2. sudo apt install apt-transport-https ca-certificates curl software-properties-common

3. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

4. sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

5. sudo apt update

6. sudo apt install docker-ce

7. sudo systemctl start docker
sudo systemctl enable docker

# Containerisation and Virtual machines

## What is a vm ?

A virtual machine is a computer file, typically called an image, that behaves like an actual computer. It can run in a window as a separate computing environment, often to run a different operating system—or even to function as the user's entire computer experience—as is common on many people's work computers.

## Multipass

Containers are packages of software that contain all of the necessary elements to run in any environment.

## Containers 

Containers are packages of software that contain all of the necessary elements to run in any environment example docker.

## Critical use

When a container needs to be used on a computer to test our apps, a hacker can easily have access to it. So the container is being launched in the vm and used. Inorder not to loss critical resources.