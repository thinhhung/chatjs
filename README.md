# Chatjs

A simple chat application using [node.js](http://nodejs.org), [socket.io](http://socket.io), and [mongoDB](http://www.mongodb.org/).

## Live demonstration
[Run the app on heroku](http://thinhhung-chatjs.herokuapp.com)

## Installation Instructions
#### Install Node.js
###### Mac

If you're using the excellent [homebrew](http://github.com/mxcl/homebrew) package manager, you can install node with one command: `brew install node`.

Otherwise, follow the below steps:

1. [Install Xcode](http://developer.apple.com/technologies/tools/).
2. [Install git](http://help.github.com/mac-git-installation/).
3. Run the following commands:

        git clone git://github.com/ry/node.git
        cd node
        ./configure
        make
        sudo make install

###### Ubuntu
1. Install the dependencies:

        sudo apt-get install g++ curl libssl-dev apache2-utils
        sudo apt-get install git-core

2. Run the following commands:

        git clone git://github.com/ry/node.git
        cd node
        ./configure
        make
        sudo make install

###### Windows
Currently, you must use [cygwin](http://www.cygwin.com/) to install node. To do so, follow these steps:

1. [Install cygwin](http://www.mcclean-cooper.com/valentino/cygwin_install/).
2. Use setup.exe in the cygwin folder to install the following packages:
  * devel → openssl
  * devel → g++-gcc
  * devel → make
  * python → python
  * devel → git
3. Open the cygwin command line with Start > Cygwin > Cygwin Bash Shell.
4. Run the below commands to download and build node:

        git clone git://github.com/ry/node.git
        cd node
        ./configure
        make
        sudo make install

For more details, including information on troubleshooting, please see the [GitHub wiki page](http://wiki.github.com/joyent/node/building-node-on-windowscygwin).

## License

The code is released under the [MIT License](http://opensource.org/licenses/mit-license.php).