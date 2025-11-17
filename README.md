# Small-Office-With-Four-Departments
This project is included most of the CCNA Topics 
This Small-Office-With-Four-Departments include :

1- Desgined the diagram

2- Name the Device => Hostname + Domain Name (used for SSh)

3- Assigning IPs

4- Router Outside interface with IP DHCP 

5- ISP Router interface with DHCP Pool 

6- On Both Router and Layer3 switch => Loopback interface => to be the Router ID

7- Trunk Ports between switches => to allow VTP

8- Create VTP on Layer 3 switch + all vlans - included Management Vlan, then 

9- On Layer 2 and 3 switches (Configure SVI for 99 vlan with different IP addresses but same subnet)

10- (On Layer 3 switch already Management Vlan is accessable, its doing inter vlan) but 
    To get access to (Layer 2 switches) Management Vlan via a router from aother subnets(or remote sessions),
    we need (default gateway on layer 2 switches to response to router)=> Default gateway will be the SVI of layer 3 switch 

11- Creating SVI on Layer 3 switches for inter-vlan routing + DHCP for each vlan 

+ Statics Routes

12- Layer 2 switches => SwitchPort Access Ports + Port Security (use violation shutDown + sticky => for auto mapping the Mac-Address with the interface) 

13- STP => change the STP Protocol to get ports up faster, enable STP PortFast + bpduguard

14- DHCP Snooping + DAI Dynamic ARP Inspection (DAI need to DHCP Snooping to be enabled) + trusted port where they are needed

15- Use LACP (mode => active) => EtherChannel for  Stream between Layer2 and Layer3 switches

16- VTY (SSH) => for Management

17- ACL + PAT
