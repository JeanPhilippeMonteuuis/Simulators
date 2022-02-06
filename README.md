# Simulators

## Dependencies Installation
sudo add-apt-repository ppa:sumo/stable
sudo add-apt-repository ppa:deadsnakes/ppa #python 3.7 venv


### Ubuntu 20.04
sudo gedit /etc/apt/sources.list
Add the following line at the end of the file:  deb http://cz.archive.ubuntu.com/ubuntu bionic main universe

### Regular
sudo apt-get update

sudo apt-get upgrade -y

sudo apt-get install bison build-essential cmake default-jre doxygen flex gcc gnome-color-chooser graphviz g++ libboost-all-dev libboost-date-time-dev libboost-dev libboost-system-dev libcrypto++-dev libgeographic-dev libopenmpi-dev libosgearth-dev libpcap-dev libqt5opengl5-dev libwebkitgtk-3.0-0 libxml2-dev nemiver openmpi-bin openscenegraph-plugin-osgearth perl python-dev python3-dev python3.7 python3.7-dev python3.7-venv qt5-default sumo sumo-tools sumo-doc tcl-dev tk-dev ubuntu-desktop wget zlib1g-dev   

## Paths Configuration

gedit ~/.bashrc #Adding the paths
source ~/.bashrc #Save changes without closing terminal

export CARLA_HOME=$HOME/src/carla-simulator
export CARLA_VERSION=0.9.13

export SUMO_HOME="/usr/local/opt/sumo/share/sumo"
export SUMO_HOME=/usr/share/sumo

export PATH=$HOME/src/omnetpp-5.6.2/bin

## Virtual Environment 
cd Path/To/Carla/

python3.7 -m venv vCarla 

source vCarla/bin/activate #To use before launching any python script in the Carla Folder

###
pip3 install lxml

## Artery
### Enable sumo-gui
cd Path/To/Artery/scenarios/artery
Edit the file omnetpp.ini: add the line *.traci.launcher.sumo = "sumo-gui"
Save the file 



## References
Installation of Omnetpp with Ubuntu 20.04: https://www.youtube.com/watch?v=oBRrhuaMxGk
