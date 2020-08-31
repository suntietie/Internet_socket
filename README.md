# Socket programming Lab
Process Communicating - socket programming on easiest computer network: client & server model with Dynamic IP Address.
## Tools
Virtualbox, Ubuntu, Vyos(Linux Debian), C
## Network Structure
client <-> router <-> server
* Provide DHCP service on internal network where VyOS will act as the default gateway and DNS server.
* All of them are accessible to my computer via ssh.
## Tutorial
* [Installing VirtualBox](https://medium.com/@codingwithmanny/installing-ubuntu-18-04-on-mac-os-with-virtualbox-ac3b39678602)
* [Building Internal Network](https://www.brianlinkletter.com/how-to-use-virtualbox-to-emulate-a-network/)
* [DHCP Server](https://docs.vyos.io/en/latest/quick-start.html#configure-dhcp-dns-servers)
* [Socket Programming](http://www.linuxhowtos.org/C_C++/socket.htm)