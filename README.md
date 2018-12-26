# T3
# Angular Material example
Anguar material is the grouding design for the modern web application and mobile app.
With the google material design, we can build attractive UI and UX, consistent and functional web applications, follow the modern web design principles like browser portability, device independence and gracefull degradation.

Please refer the [office docs](https://material.angular.io) for more.

# initial the project
## 1. setup the environment
### a. install nvm on the osx
NVM is the node version manager - it use simple bash scripts to simplify the node environment dependency and manage the multiple version of the node runtime.

(NVM github)[https://github.com/creationix/nvm.git]
Download the install script using cURL and install it to current user environment.

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

Add the following line to the .zshrc or .bashrc to enable nvm

export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

Basic usage:
nvm ls -- list current installed nodejs version
nvm ls-remote -- list nodejs official release version

nvm install 10 or 10.4.2 or lts

nvm use 10 -- activate the version 10 
nvm alisa default 10 -- make version 10 as the default


# First of all, Hello world

