# Simulators

## Dependencies
sudo add-apt-repository ppa:sumo/stable

### Ubuntu 20.04
sudo gedit /etc/apt/sources.list
Add the following line at the end of the file:  deb http://cz.archive.ubuntu.com/ubuntu bionic main universe

### Regular
sudo apt-get update

sudo apt-get upgrade -y

sudo apt-get install bison build-essential cmake default-jre doxygen flex gcc gnome-color-chooser graphviz g++ libboost-all-dev libboost-date-time-dev libboost-dev libboost-system-dev libcrypto++-dev libgeographic-dev libopenmpi-dev libosgearth-dev libpcap-dev libqt5opengl5-dev libwebkitgtk-3.0-0 libxml2-dev nemiver openmpi-bin openscenegraph-plugin-osgearth perl python-dev python3-dev qt5-default sumo sumo-tools sumo-doc tcl-dev tk-dev ubuntu-desktop wget zlib1g-dev   

## PATH

gedit ~/.bashrc #Adding the paths
source ~/.bashrc #Save changes without closing terminal

export CARLA_HOME=$HOME/src/carla-simulator
export CARLA_VERSION=0.9.13

export SUMO_HOME="/usr/local/opt/sumo/share/sumo"
export PATH=$HOME/src/omnetpp-5.6.2/bin

## References
Installation of Omnetpp with Ubuntu 20.04: https://www.youtube.com/watch?v=oBRrhuaMxGk
