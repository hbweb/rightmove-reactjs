# rightmove-reactjs
Building alike Rightmove search functionality with React.js


# Preparation 
Let assume that we have nothing to start with, we never heard of React.js, Webpackjs, Nodejs etc.. 
I myself have spent sh*t load of time setting up the enviroment as so many f**king tutorial out there
using so many different module, dependency managers and tools - I ends up with so many rubblish on my Mac and very messy.

Okay, let say I want to clean out my Mac with a fresh installation for my workspace to get this up.

We are going to use Webpack, Nodejs, Homebrew, NPM, ReactJS for this project.

1. Cleanup  - Following this to remove any nodejs, npm installed on your Mac OS and do it all again.

  1	go to /usr/local/lib and delete any node and node_modules
  2	go to /usr/local/include and delete any node and node_modules directory
  3	if you installed with brew install node, then run brew uninstall node in your terminal
  4	check your Home directory for any local or lib or include folders, and delete any node or node_modules from there
  5	go to /usr/local/bin and delete any node executable
  You may need to do the additional instructions as well:
  1	sudo rm /usr/local/bin/npm
  2	sudo rm /usr/local/share/man/man1/node.1
  3	sudo rm /usr/local/lib/dtrace/node.d
  4	sudo rm -rf ~/.npm
  5	sudo rm -rf ~/.node-gyp
  6	sudo rm /opt/local/bin/node
  7	sudo rm /opt/local/include/node
  8	sudo rm -rf /opt/local/lib/node_modules
  9	sudo rm -rf /usr/local/include/node/

  Install Nodejs with Homebrew
  `brew install node`

2. 
