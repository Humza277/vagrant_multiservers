This Repo contains the code needed to create two VM's inside one vagrant file 
It also starts a Mongo db on the seccond VM 
In order to do this I also had to create a new provision file that installed MongoDB for server use 

To do this i needed to create a second VM within the Vagrantfile 
  set the box to ubuntu 
  set the network IP to something I can remember 
  and then set the path of a new provision.sh folder that i have created 


This allowed me to create two VMs within Vagrant 
