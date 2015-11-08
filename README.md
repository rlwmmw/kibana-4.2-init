# kibana 4.2 init.d script

This is a very straight forward init.d script for running Kibana 4.2

## Warning
!!!USE THIS SCRIPT AT YOUR OWN RISK!!!

This has been tested on Ubuntu 14.04.3 LTS, but it should work on any system that uses modern init.d scripts. 

I offer no warranties or assurances that this script will work with your particular build.
Feel free to fork it if you'd like to make any changes.

I appreciate any opportunity to improve it.

## Instructions

Download the raw file, allow execution, copy to /etc/init.d, and add to update-rc.d

    
    cd /tmp
    wget https://raw.githubusercontent.com/rlwmmw/kibana-4.2-init/master/etc/init.d/kibana
    sudo chmod +x kibana && sudo mv kibana /etc/init.d
    sudo update-rc.d kibana defaults
    

## Usage: 

    service kibana {start|stop|restart|status|reload}
