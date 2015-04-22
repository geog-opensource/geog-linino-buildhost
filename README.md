GeoG Draguino/Linduino Build Host
---------------------------------

### Introduction

This Serves as the LXC Image with pre-installed dependencies for
building geog-linino.

### Installation

Ensure you have lxc lxc-extra and lxc-templates installed.

Extract the debian-build.7Z and move debian-build to /var/lib/lxc/ 

Move geog-linino into /var/lib/lxc/debian-build/rootfs/

Now start the VM with:

    lxc-start -n debian-build

Now log on to the VM as root, password root.

Switch to build user:

    su - build
