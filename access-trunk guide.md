# CCNA-switchport-mode-access-trunk
CCNA-switchport mode access-trunk
access/trunk ports are used to dectate which ports are conected to other switches and which is connected to end points
to protect the network
>en
#conf t
fig#int f#/# (port to end-point)
if#switchport mode access
if#exit
fig#int f#/# (port to another switch/router)
if#switchport mode trunk (if this comand doessn't work use the next command first then use this command again.)
if#switchport trunk encap dot
