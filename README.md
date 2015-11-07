# kibana 4.2 init.d script
init.d script for Kibana 4.2

This has been tested on Ubuntu 14.04.3 LTS, but it should work on any system that uses modern init.d scripts. 

Save this script to /etc/init.d/kibana

type sudo update-rc.d kibana defaults

Usage: service kibana {start|stop|restart|status|reload}

