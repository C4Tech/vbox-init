vbox-init
=========

a script to start vbox
virtualbox goes in /etc/default/
vbox-init goes in /etc/init.d/
c4vbox foes in /usr/local/bin/


You need to add /etc/vbox/vmlist and put your list of VMs
example

MACHINENAME:SID:REMOTEPORT

"winXP":506bbd28-14d3-4f46-899a-18205099a98f:4001


To get an list of virtualbox run, as the vbox user

vboxmanage list vms

 - MACHINENAME = according to vbox
 - SID

vboxmanage showvminfo MACHINENAME| grep TCP/Ports

 - REMOTEPORT
