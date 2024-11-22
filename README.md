# ubuntu20.04_jetson_container
Devcontainer for Ubuntu 20.04 (for use to flash Jetson SDKmanager)

## Instructions for setting up the container

1 - Update the OS: `apt-get -y update`
2 - Install sdkmanager from .deb file: `sudo apt install <path to .deb file>`
3 - Run the application: `sdkmanager`

## Instructions for adding a new user with sudo rights
1 - Install sudo: `apt-get install sudo -y`
2 - Add a new user: `adduser <username>`
3 - Give user sudo rights: `usermod -aG sudo <username>`
4 - Switch to created user: `su - <username>`

