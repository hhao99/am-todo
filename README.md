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

$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash

Add the following line to the .zshrc or .bashrc to enable nvm

$ export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

Basic usage:
$ nvm ls -- list current installed nodejs version
$ nvm ls-remote -- list nodejs official release version

$ nvm install 10 or 10.4.2 or lts

$ nvm use 10 -- activate the version 10 
$ nvm alias default 10 -- make version 10 as the default


### b. configure the npm mirror
for the known reason, we need config the local mirror to accelerate the npm package download.

* method 1: install the cnpm
$npm install -g cnpm # add the taobao mirror customized command

* method 2: config the mirror registry

$ npm config set registry http://registry.npmjs.eu
or
$ npm config set registry http://r.cnpmjs.org
or
$ npm config set registry http://registry.npm.taobao.org/
$ npm install


### install the angular-cli
Angular-cli is the command line tools to help to create the angular project, maintain the package dependency, add the the scaffold to the project and configure the project to use webpack and typescript. The CLI also help us to add components, directives, services etc to existing project.
Angular-CLI use the webpack to package the project source code, to enable the typescript transpile support, Karma for the unit testing and Protractor for an end to end testing. It's the right way to start the angular project.

To install the Angular cLI, run the following command:
$ npm install g @angular/cli



# First of all, Hello world
Fisrt of all, we start the angular new project to display the hello world message to the web page.

## use angular-cli to create new project
To create a new angular project:
$ng new am-todo

and the change directory to the project and start the project:
ng serve -o

it will open the default browser to display the main web page.

## inspect the default project structure


## customized the main page message



