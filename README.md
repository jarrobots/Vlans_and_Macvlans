# How to create vlans and macvlans in Linux/GNU
## Enviroment
### OS
For this tutorial I will use the Debian OS and scripts are written in bash. Egzamples should  work for Raspbian OS, because it's kernel is inherited from Debian.
### Tools
In script I'm using packages iproute2 and net-tools

**net-tools:** 
Net-tools is a collection of programs that form the base set of the NET-3 networking distribution for the Linux operating system. This collection contains a few, mostly now obsolite, programs like ifconfig(obsoleted by ip from iproute2), which is used int this tutorial

**iproute2:**
 Iproute2 is a collection of utilities for controlling TCP / IP networking and traffic control in Linux. Iproute2 consists several tools, of which one fo the most important is ip used in in this tutorial.

The current iproute2 source is maintained in the GIT repository. To get the current source use:
```
$ git clone https://github.com/iproute2/iproute2.git
```