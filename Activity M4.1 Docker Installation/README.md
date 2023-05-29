# Docker Installation Walkthrough

# Introduction

This guide pretends to guide the user on how to install an Ubuntu image and create a simple hello world file with Python using Docker Engine.

1. Install Docker Desktop visit official site [here]([url](https://www.docker.com/products/docker-desktop/)).

2. Get official ubuntu image from [here]([url](https://hub.docker.com/_/ubuntu)). In my case, I used the ubuntu 22.04 veersion. For this, open your prefered terminal and type the command like shown here:

`docker pull ubuntu:22.04`

3. Once installed, run the image with the following command in your prefered terminal:

`docker run -it ubuntu:22.04`

You should see something like this `root@7567e5ee6089:/# `.

4. Install Python and its necessary dependencies:

```
# apt-get update
# sudo apt-get -y install python3-pip
```

5. To verify the installation, run the following command to cross check the version number:

`pip3 --version`

6. Run `python`, then print a string in your terminal:

```
# python3
>> print("Hello World From Ubuntu Docker Image!")
```

7. You should see your message _Hello World From Ubuntu Docker Image!_ printed in your terminal. Enjoy coding!
