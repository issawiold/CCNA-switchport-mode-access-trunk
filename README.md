# CCNA-switchport-mode-access-trunk

Access/trunk ports are used to dictate which ports are connected to other switches and which are connected to endpoints. This configuration helps protect the network.

\>en  
\#conf t  
fig#int f#/# (port to end-point)  
if#switchport mode access  
if#exit  
fig#int f#/# (port to another switch/router)  
if#switchport mode trunk  
if#switchport trunk encapsulation dot1q  
if#exit  
\#copy run star
